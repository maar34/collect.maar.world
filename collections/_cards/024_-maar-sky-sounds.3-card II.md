---
layout: article
show_title: false
header:
  theme: dark
  background: 'linear-gradient(135deg, rgb(0, 255, 0), rgb(139, 34, 139, .1))'
#tags: Maar SkySounds Card
cover: https://www.dropbox.com/s/y8d8mwund92zsf1/Thumb_SkySounds_3_2.jpg?raw=1

titles:
  # @start locale config
  en      : &EN       Sky Sounds.1 Card II
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN

  # @end locale config
key: world-information
---
<br>
<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/vmyhdqozq6woo0f/SkySounds3_2.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h2>Card II:</h2>
    </div>
    <div class="item__description">
      <p> In the south, life thrives in the vast expanse of the sky and the depths of the sea. The warm winds and endless horizon of the southern skies are home to a diversity of winged creatures, from the tiniest kind of hummingbirds to the majestic kind of condors. Similarly, the warm waters of the southern seas are teeming with an abundance of life, from the tiniest plankton to the largest sort of whales. Both the air and the water are essential for the survival of these creatures and the balance of life on this planet. The southern skies and seas are not only a source of life, but also a source of inspiration, from the traditional indigenous songs and dances that celebrate the winged creatures of the sky to the jazzy rhythms that pay homage to the ocean's inhabitants. They remind us of the importance of preserving these ecosystems for future generations and the interconnectedness of all living things.

</p>
    </div>
  </div>
</div>


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
        displayText.innerHTML = "Buy ENT Card - 0.34 eth";
        break;
      case "https://maarworld.gumroad.com/":
        displayText.innerHTML = "Buy Physical Card - 0.34 eth";
        break;
      case "https://opensea.io/":
        displayText.innerHTML = "Buy NFT Card - 0.34 eth ";
        break;
      default:
        displayText.innerHTML = "< Select your Card Type";
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

### Snippet

Please <a href="https://support.apple.com/en-gb/HT208353" rel="unmute" target="_blank"> unmute</a> 
your device and press PLAY ▶️ button. 

<div class="container">
  <iframe class="responsive-iframe" src="https://play.maar.world/?g=8&d=0&c=0" style="border: 0" ></iframe>
</div>







