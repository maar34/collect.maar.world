---
layout: article
show_title: false
header:
  theme: dark
#tags: Maar SkySounds Card
cover: https://www.dropbox.com/s/annm9o8t07jxrzs/Thumb_SkySounds_1_1.png?raw=1

titles:
  # @start locale config
  en      : &EN       Maar Sky Sounds.1
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN

  # @end locale config
key: world-information
---

# Skylight.1


<div class="p-4">
  <div class="padding: ($spacer * 1.5); margin-top: $spacer*4;">
    <select class="select" id="link-selector">
      <option value="https://maarworld.gumroad.com/l/Skylight-1-Suit">Physical</option>
      <option value="https://opensea.io/collection/maar-world-collections">Digital</option>
    </select>
    <button class="button button--primary  button--rounded" id="go-button">Buy</button>

    <div id="display-text" style="margin-top: 20px;"></div>

  </div>
</div>

<script>
  const linkSelector = document.querySelector("#link-selector");
  const displayText = document.querySelector("#display-text");

  linkSelector.addEventListener("change", function() {
    const selectedValue = linkSelector.value;
    switch (selectedValue) {
      case "https://maarworld.gumroad.com/l/Skylight-1-Suit":
        displayText.innerHTML = "Buy Physical Suit";
        break;
      case "https://opensea.io/collection/maar-world-collections":
        displayText.innerHTML = "Buy NFT Suit ";
        break;
      default:
        displayText.innerHTML = "< Select your Suit Type";
    }
  });

  // Trigger the change event manually to show the selected option value on page load
  linkSelector.dispatchEvent(new Event('change'));

  const goButton = document.querySelector("#go-button");
  goButton.addEventListener("click", function() {
      const selectedLink = linkSelector.value;
      window.open(selectedLink, "_blank");
    });
</script>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/annm9o8t07jxrzs/Thumb_SkySounds_1_1.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card I:</h4>
    </div>
    <div class="item__description">
      <p>The north of Maar World is a place where the ground and water sing in harmony, yet it is also a place where the wildness of nature can be both beautiful and terrifying. The cliffs echo with the roar of the sea, and the forests rustle with the gentle flow of streams, creating a symphony of sound that is both serene and fierce. The inhabitants of the north have always listened to the songs of their land and they have woven them into their music, entangled flutes sing like the wind creating a melody that reflects the soundscapes of their surroundings. They have learned to appreciate the beauty and power of nature, yet also respect its potential dangers. The water and ground of the north have shaped their culture and society, teaching them to live in harmony with the elements and to respect their power. The soundscapes of the north are a reminder that we are all connected to the land and that there is always more to discover in the beauty and mystery of the multiverse.
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/sv4sn8neh5elkap/Thumb_SkySounds_1_2.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card II</h4>
    </div>
    <div class="item__description">
      <p>Beneath the towering mountains, when groundwater comes into contact with magma, it creates a unique and powerful force of nature. The energy released by the interaction of the water and the molten rock creates a phreatomagmatic eruption, resulting in the formation of a Maar, a type of volcanic crater. These craters are shallow, circular and filled with a tranquil lake, surrounded by a variety of colors. The Maar not only shapes the planet's geology but also influences the climate and water cycle, providing water for the diverse array of life forms that flourish on the planet.
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/padgzp4ai4ydh3o/Thumb_SkySounds_1_3.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card III</h4>
    </div>
    <div class="item__description">
      <p>At the foot of a majestic mountain, volcanic craters are not just gaping holes in the ground, but also portals to the fiery heart of the planet. These craters can vary in size and shape, from small, bowl-shaped depressions to massive calderas that span miles. They are a reminder of the raw power of the ground's internal forces and the constant changes that shape this world. They also play a crucial role in shaping geology and climate, and can even create new habitats for unique forms of life. The study of volcanic craters can give us insight into the inner workings of the planet and the forces that shape it. 
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
  <img class="image image--lg" src="https://www.dropbox.com/s/lyidkkvd18m2ima/Thumb_SkySounds_1_4.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card IV</h4>
    </div>
    <div class="item__description">
      <p>The voice of water is heard in many corners of the world, it sings in the rivers, whispers in the streams, and roars in the sea. The water is a constant companion, shaping the land and the lives of its inhabitants. Different species have always listened to the voice of the water, and they have woven it into their music, stories, and legends. Water is a vital source of life, providing nourishment for the world and sustaining all living things. It is also a force that shapes the land, carving canyons and creating powerful floods. The voice of water reminds us of its importance for life, and the need to respect and preserve it. It is a reminder that water is not just a resource, but a fundamental part of the natural world to be protected and respected.
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/5gqvdbu52jb8vt7/Thumb_SkySounds_1_5.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card V</h4>
    </div>
    <div class="item__description">
      <p>The voice of fire is heard in the world, it speaks in the tongues of volcanoes and whispers in the embers of campfires. Fire is a force of nature, both destructive and transformative. The people of Maar have always been fascinated by the voice of fire, and they have woven it into their myths and legends. Fire is a reminder of the power of the world and its ability to create and destroy. It is a source of warmth and light, but also a source of danger, capable of burning down forests and devastating communities. The voice of fire reminds us of its importance and the need to respect and harness its power. It is a reminder that, like all-natural elements, the fire must be respected and understood, in order to be able to live in harmony with it.
</p>
    </div>
  </div>
</div>






<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/a33ban5469w2ro3/Thumb_SkySounds_1_6.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card VI</h4>
    </div>
    <div class="item__description">
      <p>In the heart of the dense forest, time is viewed from a different angle, one that follows global water cycles. Time is understood not only as linear but also cyclical, and the cycles of water are seen as a reflection of this. The movement of water is viewed as a dance, from the gentle flow of a stream to the crashing of the ocean waves, and the importance of this dance for the balance of life on the planet is acknowledged. The cycles of water are studied to gain knowledge about the planet and how different cultures perceive time. Different perspectives on time are acknowledged and how they can affect the interaction with the environment. The interconnectedness of time, water and life is understood, and how understanding these connections can help preserve the planet's resources. The study of the cycles of water is recognized as a way to understand the past, present and future and how it affects the culture and way of life.
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/namm02686xxyvck/Thumb_SkySounds_1_7.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card VII</h4>
    </div>
    <div class="item__description">
      <p>Under the glow of the fiery suns, all the states of water, whether it be in the form of precipitation, ice melt or flowing water, are interconnected and hold a unique beauty and importance. The circularity of water is observed, how it goes from the sky to the ground, to the rivers, and back to the sky, creating a closed loop. The value and importance of each state of water for the balance of life on the planet is recognized and the need to preserve them is acknowledged. These states are not seen as separate entities but rather as different manifestations of the same underlying element. The beauty of the different forms water takes is appreciated, from the softness of a raindrop to the strength of a river, and it is acknowledged that all these states are essential for the well-being of the planet and all its inhabitants. 
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/va57myik7x3nzsr/Thumb_SkySounds_1_8.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card VIII</h4>
    </div>
    <div class="item__description">
      <p>In the depths of the underground caverns, the acoustic coloration is caused by echoes, reverberations and effects related to climatic factors. It is understood that the sound of the land is not just background noise, but a fundamental part of the natural world to be respected and protected. The use of these echoes and reverberations to create music and stories that reflect the soundscapes of the surroundings is an advantage. The acoustic coloration is also acknowledged to be affected by the climate, and the ability to predict and adapt to these changes is developed. The sound of the land is seen as a reminder of the beauty and power of nature and the importance of preserving it for future generations.
</p>
    </div>
  </div>
</div>





<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/urey5kenosu7ftn/Thumb_SkySounds_1_9.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card IX</h4>
    </div>
    <div class="item__description">
      <p>In the midst of a fertile, rolling farmland, the portals between dimensions are not only a scientific marvel but also a cultural treasure. These portals are created through the study of water's heat and its role in regulating the climate. The interconnectedness of things and the beauty that lies beyond our physical realm is a fascination. Water is recognized as not just a resource but an essential element of the natural world, shaping the land and the climate and also serving as a gateway to other realms. The signs of the water's movement are read, and the annual cycles of precipitation, ice melt, and water flow are anticipated, using the heat of water and music to unlock portals to other dimensions. Rituals underwater, new ways of listening to music, and new ways of making it can be learned. Preserving natural cycles is understood to be crucial for the preservation of the way of life, the planet's ecological balance, and access to other realms.
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/2jjqw5eyrkbz3cu/Thumb_SkySounds_1_10.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card X</h4>
    </div>
    <div class="item__description">
      <p>In the midst of a thriving city surrounded by nature, a healthy soundscape is essential in preventing polarization and fostering a sense of unity and community. The power of sound and its ability to shape the way we perceive and interact with our surroundings is acknowledged. Living in harmony with the natural soundscapes is a way of life and music is created that reflects the beauty and diversity of the surroundings. Sound is understood to be capable of bringing people together and fostering a sense of community. At the same time, it is also acknowledged that sound can be used to divide and create conflict. Efforts are made to create a healthy soundscape, one that is diverse, inclusive, and respectful of different perspectives. By preserving a healthy soundscape, a more harmonious and united community is created, one that is less prone to polarization and division.
</p>
    </div>
  </div>
</div>





<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/t6dtqcmspw2v4e1/Thumb_SkySounds_1_11.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card XI</h4>
    </div>
    <div class="item__description">
      <p>Beneath the roots of the ancient, towering trees, the inhabitants have had to learn to recognize the importance of each element, from the tiniest microbe to the largest mountain, and their role in the balance of the natural world. Despite this understanding, there have been times when the exploitation of resources has threatened the planet's biodiversity and the well-being of its inhabitants. The laws of physics and chemistry have shown that resources are interconnected, but it is a constant challenge to navigate these connections in order to use them sustainably. It is also a challenge to reconcile the sacredness and value of these resources with the need for development and progress. The inhabitants of Maar continue to strive for balance and harmony, but it is a constant evolution process that requires constant adaptation and resolution of issues that arise.
</p>
    </div>
  </div>
</div>



