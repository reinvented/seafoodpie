# Hon. Wade MacLauchlan's Seafood Pie Recipe

On Sunday, December 20, 2015, [Hon. Wade MacLauchlan](http://www.gov.pe.ca/premier/), Premier of Prince Edward Island, called the [CBC Radio One program Cross Country Checkup](http://betterembedder.appspot.com/?q=2680704463), responding to the question "What is your winter comfort food?" with a description of his recipe for seafood pie.

It cannot have been lost on the Premier that he was following in the tradition of his [biographical subject](http://alexbcampbell.com/), and predecessor, Alex B. Campbell, [who appeared on CBC Morningside with Peter Gzowski in 1990](http://www.cbc.ca/archives/entry/pei-elections-chief-chef-joe-ghiz) and made a Caesar salad.

The Premier followed up on December 23, 2015 by [posting the recipe to Twitter](https://twitter.com/wademaclauchlan/status/679678844639547392). Unfortunately, the Twitter recipe was imprisoned in [a low-resolution JPEG image](seafoodpie.jpg), anathema to any citizen cook concerned with open data.

As a service to the province, thus, I present the Premier's recipe in various open formats, with hopes that this will aid in its flourishing. 

## HTML

The **[seafoodpie.html](seafoodpie.html)** file is an HTML version of the recipe, with the recipe components wrapped in RDFa, using [the Schema.org Recipe vocabulary](https://schema.org/Recipe), so that, for example, the ingredients that look like this to the naked eye:

* 20 lbs fresh mussels
* 5 bottles bar clams
* 5 lobsters
* 3 lbs scallops
* 3 lbs salmon fillets
* 2 lbs trout fillets
* 5 lbs starchy potatoes
* 5 to 10 cups of finely chopped green onions, fennel and/or celery
* Dill, oregano, caraway and black pepper to taste
* 3 eggs
* 20 pie shells

under the hood look like this:

    <ul>
      <li property="recipeIngredient">20 lbs fresh mussels</li>
      <li property="recipeIngredient">5 bottles bar clams</li>
      <li property="recipeIngredient">5 lobsters</li>
      <li property="recipeIngredient">3 lbs scallops</li>
      <li property="recipeIngredient">3 lbs salmon fillets</li>
      <li property="recipeIngredient">2 lbs trout fillets</li>
      <li property="recipeIngredient">5 lbs starchy potatoes</li>
      <li property="recipeIngredient">5 to 10 cups of finely chopped green onions, fennel and/or celery</li>
      <li property="recipeIngredient">Dill, oregano, caraway and black pepper to taste</li>
      <li property="recipeIngredient">3 eggs</li>
      <li property="recipeIngredient">20 pie shells</li>
    </ul>

## JSON+LD

The **[seafoodpie.json](seafoodpie.json)** file is an [JSON+LD](http://json-ld.org/) version of the recipe, using the same [Schema.org Recipe vocabulary](https://schema.org/Recipe), so that, for example, the ingredients above look like this:

	"recipeIngredient": [
	 "20 lbs fresh mussels",
	 "5 bottles bar clams",
	 "5 lobsters",
	 "3 lbs scallops",
	 "3 lbs salmon fillets",
	 "2 lbs trout fillets",
	 "5 lbs starchy potatoes",
	 "5 to 10 cups of finely chopped green onions, fennel and/or celery",
	 "Dill, oregano, caraway and black pepper to taste",
	 "3 eggs",
	 "20 pie shells"
	],

# License

One presumes that the original recipe is Hon. Wade MacLauclan's and it certainly appears here without any sort of formal permission for reuse, so if you want to publish it in a recipe book or add it to your restaurant's menu, I suggest [you ask him](http://www.gov.pe.ca/premier/index.php3?number=1029925&lang=E).

I'm [Peter Rukavina](http://ruk.ca/), and I did this simply as a demonstration of why open is better.