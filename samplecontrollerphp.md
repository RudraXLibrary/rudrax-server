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
	public function renderTemplate(){
		include "contact.php";
	}
	
	/**
	 * @RequestMapping(url="aboutme")
	 */
	public function dataHandler(){
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
