# SampleController.php

```
include_once(RUDRA."/core/controller/AbstractController.php");

/**
 * @Controller
 */
class SampleController extends AbstractController{
	
	/**
	 * @RequestMapping(url="/contactme")
	 */
	public function contactmepage(){
		include "contact.php";
	}
	
	/**
	 * @RequestMapping(url="aboutme")
	 */
	public function aboutMePage(){
		 include "mypages/aboutme.html";
	}
	
	/**
	 * @RequestMapping(url="")
	 */
	public function homePage (){
		echo "This is Home page";
	}
}

```
* There is no rule for method name, name it the way you wisht to.
* This file should be placed in  app/controller/
* Name of file should be same as Class name ( eg: SampleController).
* Class must extend AbstractController


