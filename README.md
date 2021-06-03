# Jiomart-webscrapping
This is my second project in Techport.

This is my ongoing project of webscrapping for Jiomart website .

This site is under continous updation at this stage  .

Basic logic for the scrapping is finalised .

Here , I have used BeutifulSoup from bs4 . and requested the url .

I got the response 200 , so i can do the webscrapping with this site .

First , I found the main categories in webpage , and then its subcategory .

On each subcategory page , got the number of products .

and in each product page , we got the comlete details of the product .

Then you can scap that data .

After completing the first page on subcategory , we can move to 2nd , 3rd upto last , if pages finishes , then we can move forward to next category .

We are here scrapping the data for all the products , and moving that data into pandas dataframe .

And finally , we are converting that Dataframe into excel and saving the same to current directory ..

