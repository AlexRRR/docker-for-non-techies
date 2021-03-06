

# Software Containerization

## Analogies
Analogies are used throughout the presentation as they allow people from very different domains
to understand complex topics, and also... I just love analogies.

## Story

### The Restaurant (Analogy for Server)

A few years ago a very talented Chef created a Restaurant, he bought a big empty building and installed by himself everything the building needed for his business: piping, bathrooms, heating, gas. He also customized a lot of the furnishings: the floor was *just* the right color, so was eveything else... decorated just the way the Chef wanted.

In a different location another Restaurant was installed and the same procedure was followed, manually installing everything trying to make the new one *exactly* like the one they installed before. It was tricky, but they were able to do it.

This country, you see... it has very strange laws, every few years you *must* change to a new building, as if one stays for too long it might just collapse. So for your own safety, you must move.

But every year, the Chef noticed that the buildings available just kept growing in size, and customers still arrived in same numbers, but a *lot* of the new buildings were empty now.

### The Multi-Restaurant (Analogy for VMs)

Now this Chef was a really smart guy and he decided that since the buildings had more space, he could install *new* kinds of Restaurants inside the same building, so they would make division walls inside, make entry doors, install new furniture, new piping, new heating, new kitchen, etc.

These Restaurants had their own entry door, neon sign, welcome mat, *everything* you would find in a real Restaurant, even though they were not *outside* the building. But if you were inside one, you would not be able to tell that this was a Restaurant inside a Restaurant.

This was fine, they could now make better use of the space, but it was getting harder and harder to get all Restaurants to be exactly alike.


### Expansion

The Restaurants were a huge success, So the Chef began to create a franchise. He would give the new franchise owners a list of *exactly* the things each Restaurants must have, the furniture, the size of the kitchen, etc. And when done, the cooks of the franchise would *execute* the very detailed recipes and serve them to the customers.

At first it was simple to verify the quality of the dishes and inspect the general facilities but as the franchise grew it became exponentially more difficult for the Chef to know exactly what was being served in all locations.

For the task of making sure that all Restaurants in the franchise were exactly the same, the Chef hired a group of people he nicknamed *the puppets* although their official position position was that of **Configuration Managers** so that appeared on their business cards. The job of these guys was visiting reach Restaurant regularly, go through their checklists of how things should be and if **anything** was different, they would return it right back to the way it was supposed to be.

These *Configuration Managers* would check that the Ingredients were obtained locally according to their list.

But as the number buildings grew, complications appeared: One Restaurant was in a very hot and humid area of the country... then the checklist would need to include an A/C setup for this Restaurant and maybe no carpeting... Oh and the ones in the Mountains would need wool seat covers and a chimney. All of these little differences grew into a huge list. Making a single change in that list was really scary, as it could potentially change everything in *every* single Restaurant, sometimes chimneys would end up at the beach.

### The Lasagne Bolognese

#### Ingredients
**Ragu Bolognese**:
5 tablespoons extra-virgin olive oil
3 tablespoons butter
1 carrot, finely, diced
1 medium onion, diced
1 rib celery, finely diced
1 clove garlic, sliced
1 pound veal, ground
1 pound pork, ground
1/4 pound pancetta or slab bacon, ground
1/2 tube tomato paste
1 cup milk
1 cup dry white wine
Kosher salt and freshly ground black pepper
Parmigiano-Reggiano, for grating
**Lasagna al Forno**
4 extra-large eggs
6 ounces frozen chopped spinach, defrosted and squeezed very dry and chopped very fine
3 1/2 to 4 cups unbleached all-purpose flour, plus 1/2 cup for dusting the work surface
1/2 teaspoon extra-virgin olive oil
**Besciamella**
5 tablespoons butter
4 tablespoons flour
3 cups milk
2 teaspoons salt
1/2 teaspoon freshly grated nutmeg
8 ounces Parmigiano-Reggiano, for grating

Read more at: [Recipe] (http://www.foodnetwork.com/recipes/mario-batali/lasagne-bolognese-al-forno-recipe.html?oc=linkback
)

### The Perfectionist Chef

The Chef greatest ambition is to receive (and keep) Michelin stars, to achieve such an honor, every single part of every dish served must be perfect, not only that it must be improved upon **constantly** as the competition is fierce and the stars scarce. In the case of the Lasagne, that would mean things like trying out new kinds of minced meat, new types of butter, adding wines from different regions, etc.

Up until now Recipes traditionally had been treated as a whole, you would take all the ingredients, cook them and taste the final product at the very end. This made tracking undesired flavors *very difficult*, and also whenever new cooks arrived at the Chefs Kitchen it would take them much longer to fully understand, master and improve the recipes. These big recipes were called *Monolithic Recipes*.

The Chef this idea of breaking down the recipes into smaller, more manageable and possibly reusable elements.

In the case of the Lasagne:
- Ragu Bolognese
- Lasagna al Forno
- Besciamella

With this method incremental improvements can be done to one specific part of the recipe, tracking problems is much simpler as they taste each component invidually and new cooks can master the recipe faster. We call this recipes *Micro Recipes*

The problem with Micro Recipes lies in the fact that some dishes are made up of dozens of these Micro Recipes and managing that in a running kitchen at peak hours was very hard. It seemed like the idea of Micro Recipes would have to wait.

### Disaster strikes

One day disaster hits, there is one bad review in the *Gourmet* magazine about the Lasagne. The review reads:
> _The tomato sauce used in the Bolognese was just too sweet for my taste_

A complete and total **disaster**!!

Now the Chef needs to go to every single restaurant (Gourmet magazine restaurant inspectors don't really tell you where they ate) to try the Lasagne and find the source of the problem.

After much research he finds that one Restaurant has been using *Campari* tomatoes and as  **everyone** knows those are extremely sweet. The Chef had used *Roma* tomatoes in his kitchen while developing the recipe.

Problem is that *Campari* tomatoes work perfectly for the Caprese Salad they serve, and the *Roma* tomatoes are simply not available fresh in this region of the country.

This is just one of the many similar cases they have spotted recently, this sort of investigation is extremely time consuming and expensive for the Chef, He could be creating new dishes or improving old ones to get those much coveted Michelin stars!

This is definitively **not** good for business.


## A Technology Breakthrough

> Any sufficiently advanced technology is indistinguishable from magic. (Clarke's 3rd law)

Scientist have come up with this fascinating new invention, it is a kind of big microwave, which you can send your existing recipe and with extremely an detailed instruction set, you can do describe anything that you can do in a normal kitchen. The outcome is a perfect rendition of the dish wrapped inside a Tupperware like _*container*_ called an *image*.

Now all the Restaurants have installed one of these machines and they get a copy of this Tupperware image, the cooks put the Tupperware image inside and can cook (run) it and get an **exact** replica of what the Chef wanted.

Not only that! The machine **clones** the container and can serve as many copies of the dish as the restaurant needs!!!

It gets even better, the machine uses many of these Tupperware containers at once with the latest parts of the Lasagne (Ragu, Lasagne, Besciamella) to create a single dish, the cooks just need to ask the machine for a _Lasagne_! The Micro Recipe problem is solved!

## Make the kitchen great again! (development environments)

Sometimes in such high-end Restaurants you need to test not only one dish, but you want to test how the dish you are developing sits in the complete **full course meal**. This meal consists of several dishes which are served to the customer in a specific order, they must be harmonious with each other not only in flavor but also in temperature and texture. In the past, the Chef developing the new dish would need to wait for all the other Chefs in the kitchen to create samples of their own dishes, and arrange a table with the full meal to test how their new development would fit in the meal. Of course they had just a limited number of test tables. Chefs waiting for other Chefs to test the full course meal was time consuming, frustrating and expensive, not to mention one could accidentally test their prototype dish against other prototypes and not the official full course meal.

Now with the Tupperware containers it it possible for a single Chef to **instantly** create complete full course meals and be able test the progress of the dish they are currently working on against exactly what is currently being served at the Restaurants.  

## Keeping customers happy (Orchestration)

Remember that weird law where you had to move out of the building every few years? Well, in order to serve the growing customer base, the Chef has decided that each location should have more than one restaurant next to each other: They will all have a common dining room and serve different types of dishes, so one might be doing Pad Thai, Steak Bernoise, but not really Lasagne. And the other Restaurants might have Lasagne but not Pad Thai.

Now people before entering the Restaurant need to place the order to a _Maître d'hôtel_, who will direct them to the correct building where their desired dish is currently being served.

In case a building is declared non-usable by the city, the _Maître d'hôtel_ can quickly inform the other Restaurant buildings to start serving the dishes that are currently not served, and ensure that all dishes available at all times.

But the _Maître d'hôtel_ is something really special, he will always periodically look at the presentation of the dish, as well as caring that it is served at just the correct temperature. In case a dish not following his strict requirements, he will ask for a new dish to be created from the Tupperware container in the Kitchen. Not only that he will also take care that the restaurant has enough and the _correct_ cutlery for serving new dishes, so say the Chef now wants to offer _Escargot de Bourgogne_, the _Maître d'hôtel_ will *only* make this dish avaiable at Restaurants that have right cutlery to serve it, you would not serve  _Escargot de Bourgogne_ with fork and knife only... we are not savages, are we?

## Some things are more complicated.

So this new world of magical Tupperware containers sounds so perfect, but it isn't it all magical. Some things are more complicated, for example think of the billing, even though a same physical building is selling different dishes, each dish served might belong to a *different* restaurant, the Lasagne to the Italian restaurant, the Pad Thai to the eh... Thai restaurant. Organizing the accounting for a single restaurant would require aggregating all of the billing per dish across all buildings in all regions.

There is also the problem of *shared storage*, think about Pad Thai, you dress the dish with lime, coriander and peanuts *after* placing it on the plate. So it cannot come from the container. To have consistency you would need to have central storage to have the *same* kind of limes, peanuts, and coriander along with the detailed quantities of each ingredient.  And if a change is done it immediately be applied to all new  Pad Thai dishes across all buildings. The storage and all of the building in the chain are connected by Pneumatic tubes. Having this shared storage that is easily reachable for all locations is very difficult to get right.

## This is not our business! (Cloud)

One still standing problem was the problem of the Buildings which you had to move out every few years and build new ones, not only that... but managing warehouses, delivering things at the right time from the central storage, scouting land for going into new territories. This whole Infrastructure problem was a little too much and it took so many resources that the Chefs instead of focusing on their business were diluting their time into other things. If there only existed a better way....

As luck would have it several years ago a very, very smart and extremely successful book salesman realized that he had gotten **extremely** good at creating this type of buildings for his own business, so much that people constantly would ask him to let them rent some space inside *his* buildings because they like them so much. He soon realized that this could be **his business**.

People could go and rent as many building as they needed for whatever needs they had, and not care about bricks, and piping, and deal with infamous old building law anymore, the book salesman would take care of all that for them. He was so successful that he could rent buildings in any region of the world. He would coordinate the central storage and ensure that it was always running!

The Chef realized that *any* new cook just fresh out of school with a good idea could just come to the book salesman and have a Restaurant chain as big as they wanted **instantly**! They could focus 100% on **their business** and make their recipes better and always keep improving the quality, but if the Chef wanted to grow more he had to take care of all those tedious and complicated tasks, he could not just compete! This was a huge danger to his business.

Now the change was very easy because of the Tupperware containers, now he could just rent the building from the book salesman, furnish it, install the microwave like machine to cook (run) the Tupperware containers and he would be ready to go! No need to make sure the rented building had the right ingredients available in its area; everything needed was already in the container!

Now there was no need to take care of the paint of the building, the floors, the pipes, the heating system, etc. The Chef could now concentrate 100% on his business and what was important for his customers.
