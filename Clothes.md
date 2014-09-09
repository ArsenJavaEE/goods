goods
=====
package com.clothes;

public abstract class Clothes {
	private  int price;
	public  String name;

	public Clothes() {
	}

	public Clothes(int price, String name) {
		this.price=price;
		this.name = name;

	}

	public float getPrice() {
		return price;
	}

	public void setPrice(int price) {
		this.price = price;
	}

	public String getName() {
		return name;
	}

	public void setName(String name) {
		this.name = name;
	}

}
