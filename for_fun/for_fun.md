---
layout: content
title: For-Fun
logo: false

images:
  plants:
    - /images/plants/monstera.jpeg
    - /images/plants/desert_rose.jpg
    - /images/plants/drago.jpg
    - /images/plants/jackfruit_tree.jpg
    - /images/plants/Poncirus_trifoliata_1_JdP.jpg
    - /images/plants/silky_dogwood.jpg
    - /images/plants/southern_pokeweed.jpg
    - /images/plants/snowball.jpg
    - /images/plants/glossy_buckthorn.jpg
    - /images/plants/gray_dogwood.jpg
    - /images/plants/common_elderberry.jpg
    - /images/plants/chestnut/chinese_chestnut_branch.jpg
    - /images/plants/chestnut/chinese_chestnut_label.jpg
    - /images/plants/chestnut/chinese_chestnut_non_viable_seeds.jpg
    - /images/plants/persimmon/common_persimmon_2.jpg
    - /images/plants/persimmon/common_persimmon.jpg
    - /images/plants/persimmon/common_persimmon_label.jpg

  mushrooms:
    - /images/mushrooms/grave_with_puffball.jpg
    - /images/mushrooms/puffball_1.jpg
    - /images/mushrooms/puffball_2.jpg
    - /images/mushrooms/puffball_grave.jpg

  birds:
    - /images/birds/poland_seagull.jpg
    - /images/birds/poland_mandarin_duck.jpg
    - /images/birds/old_lyme_fake_swans.jpg
    - /images/birds/turkeys_boston.jpg
    - /images/birds/bluejay.jpg
    - /images/birds/pigeon_comic.jpg
    - /images/birds/pigeon_1.jpg
    - /images/birds/ugly_pigeon.jpg
---

<style>
.photo-row {
  display: flex;
  gap: 10px;
  flex-wrap: wrap;
  justify-content: center;
}
.gallery-img {
  width: 33%;
  height: auto;
  border-radius: 10px;
}
.mixed-photo-grid {
  column-count: 2;          /* Creates a natural waterfall layout */
  column-gap: 10px;
}
.auto-img {
  width: 100%;
  margin-bottom: 20px;
  break-inside: avoid-column;  /* Prevent weird breaks */
  border-radius: 10px;
}
</style>

<h1>Mostly plants, urban foraging, books and birds...</h1>

<p><em>November 11, 2025. As any one who knows me well could tell you, I absolutely adore pigeons. I don't understand why everyone is so against pigeons. The rock pigeon was one of the first birds domesticated and was used to carry messages (up to 1,000 miles) for thousands of years, and even during the two World Wars (see this link on Pigeon Post: https://en.wikipedia.org/wiki/Pigeon_post). As a frequent traveler between Boston and NYC, I see many pigeons. And it is in my professional opinion that the most beautiful pigeons can be found in Washington Square Park, and the not-most-beautiful are in Boston's Backbay station.

As aside, here is the wikipedia entry for IP over Avian Carriers (https://en.wikipedia.org/wiki/IP_over_Avian_Carriers). </em></p>

<div class="mixed-photo-grid">
  {% for img in page.images.birds limit:3 offset:5 %}
    <img src="{{ img | relative_url }}" class="auto-img">
  {% endfor %}
</div>

*---*

<p><em>November 10, 2025. As a JHU alumna I will forever and always be a bluejay at heart. However, I don't know if you have every met a bluejay, but they are the meanest birds known to man. They will atack any bird that breathes around them.... Anyways, here are some fun facts about bluejays: blue jays aren't actually blue (who woulda thunk it), they belong to the Corvidae family of birds (same family as Ravens and Crows), and they love acorns! Here is a bluejay looking very regal on a electrical wire.</em></p>

<div class="photo-row">
  {% for img in page.images.birds limit:1 offset:4 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>September 20, 2025. Cambridge, MA. American persimmon, common persimmon, eastern persimmon, possume apples... there are many names for the Diospyros virginiana. This tree ranges from Florida to New England and has apparently been cultivated for its fruin since prehistoric times by Native Americans. This is a dioecious tree meaning there needs to be a female and male tree for fruit to be produced. Persimmons are super yummy, but be careful not too pick them if they are not fully ripe as they are very very very astringent when unripe. A fun fact about the common persimmon: the scientific name, Diospyrus, means "fruit of the gods" or "divine fruit", directly translating to "Zeus's wheat". </em></p>

<div class="photo-row">
  {% for img in page.images.plants limit:3 offset:14 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>September 18, 2025. Found a beautiful Chinese chestnut (Castanea mollissima) at Mt. Auburn Cemetery. Chinese chestnuts are super delicious and thus the squirells LOVE them. All I could find was these 5 non-viable nuts (non-viable meaning they are not able to germinate or sprout). You can tell a chestnut nut is non-viable if it small, shrivelded, and has a soft exterior. Apparently squirrels can tell which nuts are viable, thus making it very hard for people like me to ever find a nice nut to plant. Nearby is an American Chestnut tree, but I was also not able to find any nuts... damn squirrels </em></p>

<div class="photo-row">
  {% for img in page.images.plants offset:11 limit:3 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>September 17, 2025. Went on a walk after work and found a Puffball mushroom (belonging to the Basidiomycota division). I am only posting the biggest one, but there was a whole herd of them in the bushes just out of view. Puffball mushrooms are famous for being edible, but I personally do not take any chances with mushrooms. Next to the mushroom was the grave of the archaelogist Thomas Whittemore, the founder of the Byzantine Institue of America. </em></p>

<div class="photo-row">
  {% for img in page.images.mushrooms offset:1 limit:3 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>September 5, 2025. Some more plants and their berries near me in Cambridge MA. From left to right: Glossy Buckthorn (poisonous!), Gray Dogwood (not toxic but not edible) and Common Elderberry (berries edible after cooking, flowers can be eatern raw).</em></p>

<div class="photo-row">
  {% for img in page.images.plants offset:8 limit:3 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>September 4, 2025. Went on a walk during my lunch break at work and saw tons of plants with berries. Are any of these berries edible? Here is an info dump from left to right: Silky Dogwood (berries are edible raw or cooked), Southern Pokeweed (berries are toxic!), and Snowball (edible when cooked). </em></p>

<div class="photo-row">
  {% for img in page.images.plants offset:5 limit:3 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>Did you know a velociraptor is actually the size of a wild turkey... </em></p>

<div class="photo-row">
  {% for img in page.images.birds offset:3 limit:1 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>Jumped out of the car in excitement when I saw these swans in a lake in Old Lyme CT only realize they were fake... not my most shining moment as a bird watcher.</em></p>

<div class="photo-row">
  {% for img in page.images.birds offset:2 limit:1 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>Was very happy to spot this cozy looking Aix galericulata (mandarin duck) on a snowy day.</em></p>

<div class="photo-row">
  {% for img in page.images.birds offset:1 limit:1 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>Often planted as decoration and security due to its pretty white flowers but sharp thorns, the Asian trifoliate orange (Citrus trifoliata) is bush invasie to the East Coast. Please avoid planting, remove when possible, and attempt to discard any fallen orange from this tree to avoid further propagation.</em></p>

<div class="photo-row">
  {% for img in page.images.plants offset:4 limit:1 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>Found this cute black headed gull seated atop a statue called Wisła, constructed as the personification of the Vistula River.</em></p>

<div class="photo-row">
  {% for img in page.images.birds offset:0 limit:1 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>My most recent trip home to Spain I had to opportunity to visit Barcelona. While there I stumbled upon a seed stand in Las Ramblas where I found the seeds for the Dracaena draco. This is an evergreen subtropical tree native to the Canary Islands, Cape Verde and Morroco. This picture shows about 4 months of growth.</em></p>

<div class="photo-row">
  {% for img in page.images.plants offset:2 limit:1 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>This is my my Adenium obesum, also known as the desert rose. Until recently, this plant had been on my plants-to-get list for over 3 years. Native to the Shel region of the Sahara and the Arabian Peninsula, this an a flowering evergreen requiring very little water. Although this plant is extremely slow growing, it can reach 10 feet in height when fully mature.</em></p>

<div class="photo-row">
  {% for img in page.images.plants offset:1 limit:1 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>

*---*

<p><em>I acquired this Monstera delciosa, commonly known as the Swiss Cheese plant, 4 years ago when it was about 10 inches tall. This plant is native to Mexico and Panama and produces a delicious edible fruit (hence the name "deliciosa"). I have changed this plant's pot 4 times and it is now in a 12 gallon pot. Can you see the bird in the picture?</em></p>

<div class="photo-row">
  {% for img in page.images.plants offset:0 limit:1 %}
    <img src="{{ img | relative_url }}" class="gallery-img">
  {% endfor %}
</div>