goods
=====
package com.clothes;

public class Shirt extends Clothes {

	public String colorCode;
	public int itemID;

	public Shirt() {

	}



	public Shirt(String colorCode, int itemID, int price, String name) {
		super(price, name);
		this.colorCode = colorCode;
		this.itemID = itemID;
	}

	@Override
	public String toString() {
		return "[ Арт.: " + itemID + " Название: " + name + "\n Цвет: "
				+ colorCode + "\n Цена: " + getPrice() + "]";
	}

	public String getColorCode() {
		return colorCode;
	}

	public void setColorCode(String colorCode) {
		this.colorCode = colorCode;
	}

	public int getItemID() {
		return itemID;
	}

	public void setItemID(int itemID) {
		this.itemID = itemID;
	}
	
	

}
