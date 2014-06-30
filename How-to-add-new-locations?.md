If you want to add locations to the [official map](http://gta5-map.github.io), make sure to read the article below. There are several steps, which are required for that:

##### 1. Find the coordinations

To find out about the actual coordinates for your new location, you can use the _coordinate/debug mode_ on the [productional map](http://gta5-map.github.io):

1. Go to the [official map](http://gta5-map.github.io) or clone the repository and run it locally.
1. Find the location where you want to add content to.
1. Right click on that location, to create a debug marker that shows you the actual coordinates (latitude and longitude)
1. You can also move the marker to update your position. The coordinates will update while you drag.

##### 2. Create the markup for the "database"

The "database" is actually just a flat file in a JSON format that stores all the breach locations. So, once you have the coordinations, you can prepare that markup:

1. Read [this article](https://github.com/gta5-map/gta5-map.github.io/wiki/Format-of-locations.json), to understand the syntax of the [`locations.json`](locations.json)
1. Open a plain text editor and paste in one of the template out of the wiki article
1. Adjust the template as you wish, add the actual descriptions, images, videos and credits and of course the coordinations that you looked up in the first step
1. Once you finished "designing" the element, you can proceed with the step

##### 3. Send me adjusted locations.json element

Now you have your location in a correct and valid format, but you still have to send it over to me, so i can review and eventually add it in the [productional map](http://gta5-map.github.io) if everything looks good. To do this you have two options. You can either:

* fork this repository, add and commit your changes and then create a pull request. This method is the most comfortable one for me because, i don't have to do anything except clicking one button to review and add your content. Downside: you have to mess with `git` and GitHub.
* just send me the `locations.json` element, via:
  * E-mail: [j@frd.mn](mailto:j@frd.mn)
  * Twitter: [@frdmn](https://twitter.com/frdmn)
  * Reddit: [/u/frdmn](http://www.reddit.com/user/frdmn)
  * IRC: frdmn @ espernet/freenode

##### 4. Wait till i reviewed, merged / added your content

Once you sent me over the new location configuration, you'll need to be patient until i reviewed it and either merged your pull request, or implemented your part of the `locations.json` into the official one.

I'll let you know once i did :)