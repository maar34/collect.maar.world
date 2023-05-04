---
layout: article
show_title: false
header:
  theme: dark
#tags: Maar SkySounds Card
cover: https://www.dropbox.com/s/6hpfq6gm8mr2xsj/Thumb_SkySounds_3_1.jpg?raw=1

titles:
  # @start locale config
  en      : &EN       Maar Sky Sounds.3
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN

  # @end locale config
key: world-information
---

# Skylight.3


<div class="p-4">
  <div class="padding: ($spacer * 1.5); margin-top: $spacer*4;">
    <select class="select" id="link-selector">
      <option value="https://maarworld.gumroad.com/l/skysound1">ENT</option>
      <option value="https://maarworld.gumroad.com/">Physical</option>
      <option value="https://opensea.io/">Digital</option>
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
      case "https://maarworld.gumroad.com/l/skysound1":
        displayText.innerHTML = "Buy ENT Suit available May 24 2023";
        break;
      case "https://maarworld.gumroad.com/":
        displayText.innerHTML = "Buy Physical Suit available May 24 2023";
        break;
      case "https://opensea.io/":
        displayText.innerHTML = "Buy NFT Suit available May 24 2023 ";
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
      // window.open(selectedLink, "_blank");
    });
</script>


<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/6hpfq6gm8mr2xsj/Thumb_SkySounds_3_1.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card I:</h4>
    </div>
    <div class="item__description">
      <p> In the world of Maar, the southern soundscapes are not only heard but felt, a blue that permeates the air and speaks to the soul. The melodies and rhythms are born from the soil and the sky, shaped by the winds and the water, and nourished by the sun's energy. These soundscapes are not just a source of entertainment, but a reflection of the natural world and a reminder of our place within it. The preservation of these soundscapes is not just an act of cultural preservation, but a recognition of the interconnectedness of all things and the impact our actions have on the natural world. The jazz-influenced melodies and rhythms that emerge from these soundscapes serve as a reminder of the beauty and complexity of the natural world. 
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/vmyhdqozq6woo0f/SkySounds3_2.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card II</h4>
    </div>
    <div class="item__description">
      <p> In the south, life thrives in the vast expanse of the sky and the depths of the sea. The warm winds and endless horizon of the southern skies are home to a diversity of winged creatures, from the tiniest kind of hummingbirds to the majestic kind of condors. Similarly, the warm waters of the southern seas are teeming with an abundance of life, from the tiniest plankton to the largest sort of whales. Both the air and the water are essential for the survival of these creatures and the balance of life on this planet. The southern skies and seas are not only a source of life, but also a source of inspiration, from the traditional indigenous songs and dances that celebrate the winged creatures of the sky to the jazzy rhythms that pay homage to the ocean's inhabitants. They remind us of the importance of preserving these ecosystems for future generations and the interconnectedness of all living things.

</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/0lpws18msevtreq/Thumb_SkySounds_3_3.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card III</h4>
    </div>
    <div class="item__description">
      <p>In the midst of a raging storm at sea, the waves are a symphony of regularity and chaos, a constant flow of energy that holds within it micro and macro frequencies. Beneath the surface, strange and beautiful beings thrive, communicating through a language of song and movement. The sea is not just a body of water, but a living entity, pulsing with life and energy. The ambient music of the sea can be heard in the crashing of the waves, the whispers of the tide, and the symphony of creatures that call it home. 
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
  <img class="image image--lg" src="https://www.dropbox.com/s/9yb62aqksee0d4r/SkySounds3_4.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card IV</h4>
    </div>
    <div class="item__description">
      <p>At the edge of a waterfall, the contrast between water and the movement of water on its surface is striking. Water, a fluid element, is constantly in motion, shaping the land and carving its way through the ground. But as it flows and crashes against the surface, it takes on a different form, one that is constantly changing and adapting. This contrast is a reminder of the power and beauty of nature, and the importance of studying and understanding it. The movement of water on the surface can be a force of destruction, carving canyons and shaping the land, but it can also be a force of creation, creating habitats and nourishing life.
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/1k2drqfriu6w17d/Thumb_SkySounds_3_5.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card V</h4>
    </div>
    <div class="item__description">
      <p>A shining mirror, a portal to dimensions beyond, reflecting the mysteries of the multiverse. A gateway to realms unknown, a glimpse into the infinite, a portal to the unknown. A window to the soul, a mirror to the mind, a gateway to the beyond, a reflection of the self. A shining mirror, a bridge between worlds, a connection to the infinite, a journey through the unknown.  nwonknu eht hguorht yenruoj a ,etinifni eht ot noitcennoc a ,sdlrow neewteb egdirb a ,rorrim gninihs A .fles eht fo noitcelfer a ,dnoyeb eht ot yawetag a ,dnim eht ot rorrim a ,luos eht ot wodniw A .nwonknu eht ot latrop a ,etinifni eht otni espmilg a ,nwonknu smlaer ot yawetag A .esrevinu eht fo seiretsym eht gnitcelfer ,dnoyeb snoisnemid ot latrop a ,rorrim gninihs A. 
</p>
    </div>
  </div>
</div>






<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/ev3uywuu583z3t4/Thumb_SkySounds_3_6.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card VI</h4>
    </div>
    <div class="item__description">
      <p>There exist species with the extraordinary ability to perceive the future. They perceive beyond the present, into the ethereal realm of what is yet to come. They listen to the whispers of time, the faint echoes of tomorrow, and understand all is interconnected. They know their actions, thoughts and emotions shape the future, and use this knowledge to guide their paths. They dance with the winds of change, sing to the stars of tomorrow, and understand that the future is not set in stone, but in the hands of those who can hear its song. They are the guardians of tomorrow, keepers of the unknown, using their gift to weave the tapestry of the future with care and intention. They are the seers of the unknown, masters of time, holding the key to shaping the future.
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/0kt97p6h3q87o60/SkySounds3_7.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card VII</h4>
    </div>
    <div class="item__description">
      <p>There exists a species with the extraordinary ability to perceive beyond the physical realm. They possess a heightened sensitivity to the subatomic realm, allowing them to see beyond the limitations of human perception. This ability is rooted in the training of their neural structure, which enables them to detect and process information beyond the typical range of human senses. They use this ability to study and understand the underlying laws of physics, delving deeper into the secrets of the multiverse. They usually are scientists, explorers, and philosophers, constantly pushing the boundaries of knowledge.
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/wk2lftpk35xamtp/Thumb_SkySounds_3_8.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card VIII</h4>
    </div>
    <div class="item__description">
      <p>Forces of attraction and repulsion are not always what they seem. The near-opposites, those things that seem to be in opposition, are often drawn together. This is true not only in the realm of physics, with the pull of magnetism, but also in the realm of philosophy. The duality of life and death, light and dark, good and evil, all hold within them a certain attraction. This attraction is not always obvious, but it is there, pulling and pushing at the same time. This is the dance of existence, the ebb and flow of life, the push and pull of the multiverse. It is a reminder that the world is not always as it seems, and that sometimes, the things we think are in opposition, are in fact, intimately connected.
</p>
    </div>
  </div>
</div>





<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/wo1iq9uodabw297/SkySounds3_9.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card IX</h4>
    </div>
    <div class="item__description">
      <p>Voices of the inhabitants fit seamlessly into the natural soundscape, like pieces in a grand symphony. The frequency and rhythm of their speech are in harmony with the songs of birds, the rustle of leaves, and the rush of water. It is as if they have learned to play a game, where the objective is to blend in with the natural world and become one with it. Their voices are not a disruption, but rather an addition to the symphony of life, adding depth and complexity to the natural soundscape. The inhabitants understand the importance of preserving this harmony, and they take great care to ensure that their voices do not disrupt the delicate balance of the natural world. They strive to be an integral part of the symphony.
</p>
    </div>
  </div>
</div>




<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/vp7zbazyly9jlpn/SkySounds3_10.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card X</h4>
    </div>
    <div class="item__description">
      <p>Recognizing the intrinsic link between the well-being of aquatic species and ecosystems and the economy, the inhabitants of this world have developed a dedicated currency that sustains the delicate balance of life in the planet's waterways. The tax paid on every transaction goes directly to the world's regeneration, nourishing and sustaining the delicate balance of life in the oceans, rivers, and inhabitants. It is a unique system, one that recognizes the inherent value of nature and the importance of preserving it for future generations. It is a currency that speaks to the soul of the planet and the spirit of its people.
</p>
    </div>
  </div>
</div>





<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/vu87kq77f0a7cr4/Thumb_SkySounds_3_11.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h4>Card XI</h4>
    </div>
    <div class="item__description">
      <p>The aquifer in the south is estimated to be approximately 34,000 km¹¹. This underground water source is crucial for the survival of many species and ecosystems in the region. Aquifers provide a reliable source of water for irrigation, drinking, and industrial use. They also play a key role in maintaining the structural integrity of the land, by preventing soil erosion and maintaining water tables. The preservation of aquifers is essential for the long-term sustainability of the planet, as it ensures the availability of clean water for future generations. The study and management of aquifers is a complex and multidisciplinary task that requires a deep understanding of hydrogeology, geology, and environmental science. The importance of protecting and preserving these vital resources cannot be overstated.
</p>
    </div>
  </div>
</div>



