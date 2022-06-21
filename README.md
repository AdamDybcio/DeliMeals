# DeliMeals - My Second Flutter App

So this is my second application in Flutter (I will not release the first one, because as my skills progressed,
I noticed that this application was terribly made and I would have to do it completely from scratch, which I would
love to do in the near future). It is a food application. It has two tabs - categories and favorites. I don't really
need to explain what's in them. The entire application has data in the form of a dummy (anyway, I was just learning such basics).
Here's what it looks like:

<img src="https://user-images.githubusercontent.com/68535467/174914730-a681c10c-9781-457c-9e2f-824f768a94c7.jpg" width="320" height="720">     <img src="https://user-images.githubusercontent.com/68535467/174914735-7506d7cc-cd57-4c97-895e-9de717fb28aa.jpg" width="320" height="720">

After clicking on any category, a list of dishes assigned to a given category is displayed (a dish could be assigned to several categories at once).

<img src="https://user-images.githubusercontent.com/68535467/174914981-7d0106a1-f8b8-4915-8aa1-a093fd48ea7b.jpg" width="320" height="720">

Of course, the page can be scrolled. After clicking on a dish, its page is displayed. There you will find a list of ingredients
to prepare the dish and steps (scrollable). You can also add the dish to your favorites and the star will turn black.
This is what this page looks like:

<img src="https://user-images.githubusercontent.com/68535467/174915164-34c2a905-ec40-4e6a-b9f6-7d1fc4d371bb.jpg" width="320" height="720">

After you add a dish (or dishes) to your favorites, they are all displayed in the favorites tab:

<img src="https://user-images.githubusercontent.com/68535467/174915298-ec2ef151-d111-457f-93aa-4c55d8837609.jpg" width="320" height="720">

There is also side navigation in the application, where you can switch between the page with dishes and filters:

<img src="https://user-images.githubusercontent.com/68535467/174915313-30893659-2967-471d-baec-70c59ace8a0f.jpg" width="320" height="720">

In the filters, we can set ourselves, for example, to display only gluten-free, lactose-free, vegetarian or vegan dishes (filters can be combined).
When saved in the upper right year, the filters are applied.

<img src="https://user-images.githubusercontent.com/68535467/174915321-bd260a40-e654-49b8-a78b-1c6830b46668.jpg" width="320" height="720">

And that's it for this app. It may not look nice, but my goal when creating an application is to learn something new.

Cons of the application:

- dummy data in the application instead of using the server or using SharedPreferences
- filters and favorite dishes reset after closing the application

What have i learned:

- creating models
- creating a basic, simple application
- MaterialPageRoute, Nagivator
- distinguish between when to use StatelessWidget and StatefulWiget
- including fonts
- using photos from the internet
- write reasonably clean code (although it is still far from being perfect)
- creating subfolders for files with various purposes

and a lot of different less important things ...

Once again, this is my second application that I already made some time ago. My level has definitely jumped up and I will prove it in my next finished apps that will be released in the days.
