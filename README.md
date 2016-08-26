

# Software containarization

## Analogies
Analogies are used throughout the presentation as they allow people for very different domains
understand complex topics, and also... I just love analogies.

## Story

### The Restaurant (Analogy for Server)

A few years ago a very talented Chefs created a Restaurant, they bought a big empty building and they installed all the piping needed, the bathrooms, installed the heating, the gas,
the floor was *just* the right color, decorated it just the way the wanted.

In a different location another Restaurant was installed and the same procedure was done, manually installing everything trying to make the new one *exactly* like the one they installed before. It was tricky, but they were able to do it.

This country, you see... it has very strange laws, every few years you *must* change to a new building, as if one stays for too long it might just collapse. So for your own safety, you must move.

But every year, the Chef noticed that the buildings available just kept growing in size, and customers still arrived in same numbers, but a *lot* of the new building was empty now.

### The Multi-Restaurant (Analogy for VMs)

Now this Chef was really smart, and he decided since they had more space, the could install *new* kinds of Restaurants inside the same building, so they would make division walls inside, make entry doors, install new furniture, new piping, new heating, new kitchen, etc.

This was fine, they could now make a better use of the space, but it was getting harder and harder to get all Restaurants to be exactly alike.


### Expansion

The Restaurants were a huge success, and they began to create a franchise. They would give a the new franchise owners a list of *exactly* the things each Restaurants should have, the furniture, the size of the kitchen. And when done, the cooks of the franchise would *execute* the very detailed recipe and serve it to their customers.

At first it was easy to very the quality of the dishes but as the franchise grew it became exponentially more difficult for the Chef to know exactly what was being served.

For the task of making sure that all Restaurants in the franchise were exactly the same, we created a group of people nicknamed *the puppets* which held the position of **Configuration Manager** on their business cards. The job of these guys was going regularly to each Restaurant, have their checklist ready of how things should be and if **anything** changed, they would return it right back to the way it was supposed to be.

These *Configuration Managers* would check that the Ingredients were obtained locally according to their list.

But as the number buildings grew, complications appeared: One Restaurant was in a very hot and humid area of the country... then the checklist would need to include an A/C setup for this Restaurant and maybe no carpeting... but not for the ones in the Mountains. All of these little complications grew into a huge list. Making a single change in that list was really scary, as it could potentially change everything in *every* single Restaurant.

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

The Restaurants aim for Michelin stars, and to achieve that every single part of the dish must be perfect, not only that but it is improved upon **constantly**, in the case of the Lasagne, trying out new kinds of minced meat, new types of butter, wine from different regions, etc.

Up until now traditionally Recipes had been treated as a whole, you take all the ingredients, cook it and taste it at the end. This made tracking undesired flavours *very difficult*, and also when new cooks arrive at the Chefs Kitchen it takes them much longer to fully understand, master and improve the recipe.

So the Chef decided to break down the recipes into smaller, possibly reusable elements, in the case of the Lasagne:
- Ragu Bolognese
- Lasagna al Forno
- Besciamella

Improvements can be done to one specific part of the recipe, tracking problems is much simpler as they taste each component and new cooks can master the recipe faster.

### Disaster strikes

One day disaster hits, there is one bad review in the *Gourmet* magazine about the Lasagne. The review reads:
> _The tomato sauce used in the Bolognese was just too sweet for my taste_

A complete and total **disaster**!!

Now the Chef needs to go to every single restaurant (Gourmet magazine restaurant inspectors don't really tell you where they ate) try the Lasagne to find the source of the problem.

After much research he finds that one Restaurant has being using *Campari* tomatoes and as  **everybody** knows those are very sweet. The Chef had *Roma* tomatoes used in his kitchen while testing the recipe.

Problem is that *Campari* tomatoes work perfectly for the Caprese Salad they serve, and the *Roma* tomatoes are simply not available fresh in this region of the country.

This just one of the cases they have spotted recently, this sort of investigation takes a *lot* of time from the Chef, when he could be creating new dishes or improving old ones. This is definitively **not** good for business.


## A Technology Breakthrough

> Any sufficiently advanced technology is indistinguishable from magic. (Clarke's 3rd law)

Scientist have come up with this fascinating new invention, it is a kind of big microwave, which you can send your recipe with extremely detailed instruction set, you can do describe anything that you can do in a normal kitchen and the outcome is your dish inside a tupperware like _*container*_ called an *image*.

Now all the Restaurants have installed one of these machines and they get a copy of this tupperware container, the cooks put the tupperware container inside and can cook (run) it and get an **exact** replica of what the Chef wanted.

Not only that! The machine **clones** the container and can serve as many copies of the dish as the restaurant needs!!!

It gets even better, the machine uses multiple of these tupperware containers at once with the latest parts of the Lasagne (Ragu, Lasagne, Besciamella) to create a single dish, the cooks just need to ask for a _Lasagne_!

## Keeping customers happy (Orchestration)

Remember the weird law where you had to change the building of your every few years? Well in order to serve growing customer, the Chef has decided that each location should have more than one restaurant next to each other. And they will serve different types of dishes, so one might be doing Pad Thai, Steak Bernoise, but not really Lasagne. And the other Restaurants might have Lasagne but not Pad Thai.

So people before entering the building place the order with a _Maître d'hôtel_ and he will send them to the correct building where their desired choice is currently being served.

In case a building is declared non-usable by the city, the _Maître d'hôtel_ can quickly inform the other Restaurant buildings to start serving the dishes that are currently not served, and ensures that all dishes available.

<<<<<<< HEAD
But the _Maître d'hôtel_ is something really special, he will always periodically look at the presentation of the dish, and care that it is served at the correct temperature. In case of the dish not following his strict requirements  he can ask for a new dish to be created from the tupperware container in the Kitchen. Not only that he will also take care that the restaurant has enough and the _correct_ cups, plates, etc, for serving new dishes, so say the Chef now wants to offer _Escargot de Bourgogne_ the _Maître d'hôtel_ will *only* add this dish to the Restaurant that has the right cutlery to handle it, you don't eat _Escargot de Bourgogne_ with fork and knife only... we are not savages are we?
=======

## Some things are more complicated.
>>>>>>> 06d3c56fdc5f26eef0fa632b59f5cfe0fbde3d33

## Some things are more complicated.

So this new world of magical tupperware containers sounds so perfect, but it isn't it all magical. Somethings are more complicated, for example think of the billing, even though a same physical building is selling different dishes, each dish the serve might belong to a *different* restaurant, the Lasagne to the Italian, the Pad Thai to the eh... Thai restaurant. Separating and later agregatting of the billing per dish across all the different buildings, to do the accountancy for a single Restaurant.

There is also the problem of *shared storage*, think about Phad Thai, you need to add lime, coriander and peanuts *after* serving it on the plate. So it cannot come from the container. To have consistency you would need to have central storage to have the *same* kind of limes, peanuts, and coriander also the detailed quantities of each ingredient. And if a change is needed when it is done it immediately applied to all buildings server Pad Thai. Having this shared storage that is easily reachable for all is difficult (but absolutely doable).
