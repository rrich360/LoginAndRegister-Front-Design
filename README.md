# LoginAndRegister-Design

This is an example of how to create a login and register form with functionality that allows the user to click on the forms to either access or close access to an application.


In the register form we will create a function (checkUsername) to check if the username you want to register is already exists in the database table

what you need to create for the user to register:

-the firstname jtextfield
-the lastname jtextfield 
- the username jtextfield 
- the password jtextfield 
- the retype_password text 
- the birthdate with jcalendarchooser
- the address jtextfield

In the login form it's simple;
the user enter his login and password and click on the login button,
and all we have to do is to check if a user with this username and password already exists on the database.  


1. First, we start with the palette in netbeans to create the front-end for the login and register panel.


![1 0-Palette](https://user-images.githubusercontent.com/20470279/60215863-9bbcac00-9836-11e9-96b4-70891868a194.JPG)


Next, you choose the color you would like to make the panel. There are some websites you can go to and pick the color and rgb code to type in the background. Once you click the section of the palette that you want to apply the color to it changes to that color.



![1 1-uicolor](https://user-images.githubusercontent.com/20470279/60216235-81cf9900-9837-11e9-8e1a-1184fa6cf87b.JPG)




![1 2-rgb](https://user-images.githubusercontent.com/20470279/60216241-84ca8980-9837-11e9-9c45-bc76baf8c101.JPG)



2. Once you’ve applied the color scheme to your login panel and you’ve inserted the jtextfields for the username and password it should resemble something like the following picture below: 



![2 0-usrpswd](https://user-images.githubusercontent.com/20470279/60216373-dffc7c00-9837-11e9-8400-d9258918289b.JPG)




2.1-- Next, you need to implement events for mouse-clicking on your panel. This would include the minimize option, the close option, and the option to go to the register panel. 



![2 1-mouseClick_LI](https://user-images.githubusercontent.com/20470279/60216488-2ce05280-9838-11e9-9bfe-28daf0e5ccc5.jpg)



2.2-- Then you should create buttons that will allow the user to either login the database or cancel to login. You also need to create a link for the user to get to the register panel in case they can not login. When creating this it’s wise to implement the hand cursor feature on the link to show that it is clickable.

				
				
				
				
![2 20-login](https://user-images.githubusercontent.com/20470279/60216654-a11af600-9838-11e9-9123-fa89948e1abd.JPG)




![2 21-loginClick](https://user-images.githubusercontent.com/20470279/60216658-a2e4b980-9838-11e9-8f7a-dbdf28f6a442.JPG)





![2 22- handCursor](https://user-images.githubusercontent.com/20470279/60216661-a4ae7d00-9838-11e9-97c5-d71d97f12632.jpg)
				
				
				
				
        
3. Now it’s time to create the Register panel. It’s the same way you created the login panel except you have to put the necessary fields inside of the panel. For the Date field section you should have a jDateChooser available inside of the palette. If you do not, you just need to download the jar file for the jDateChooser into the palette for netbeans. It should load it automatically or you can restart netbeans and then you should be able to find the feature for the date chooser in the palette. 




![3 0-JDate](https://user-images.githubusercontent.com/20470279/60216821-11c21280-9839-11e9-8830-a2f479158e5c.JPG)



![3 0-JDateChooser](https://user-images.githubusercontent.com/20470279/60216826-138bd600-9839-11e9-9378-dfebe3a10691.JPG)






3.1-- Next, you need to create the click events for the necessary options on the Register panel (minimize, close, or go to login). Then you need to create the button to register in the database or to cancel. 



![3 1-register](https://user-images.githubusercontent.com/20470279/60216903-5188fa00-9839-11e9-9dd1-ec656409a961.JPG)




![3 1-registerClick](https://user-images.githubusercontent.com/20470279/60216909-5352bd80-9839-11e9-9117-2747563dbcf7.JPG)


