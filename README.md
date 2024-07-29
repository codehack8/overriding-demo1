# overriding-demo1
package com.qis.corejava.final1;

 class Myclass{
  final	 public void mydata() {
			System.out.println("super  class Myclass method");
		}
 }
public class OverridingDemo extends Myclass{	
	public void mydata1() {
		System.out.println("sub class mydata method");
	}
	public static void main(String[] args) {
		OverridingDemo od= new OverridingDemo();
		od.mydata();
	}

}
