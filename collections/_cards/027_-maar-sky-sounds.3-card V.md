---
layout: article
show_title: false
header:
  theme: dark
  background: 'linear-gradient(135deg, rgb(0, 255, 0), rgb(139, 34, 139, .1))'
#tags: Maar SkySounds Card
cover: https://www.dropbox.com/s/1k2drqfriu6w17d/Thumb_SkySounds_3_5.jpg?raw=1

titles:
  # @start locale config
  en      : &EN       Maar Sky Sounds.3 Card V
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
    <img class="image image--lg" src="https://www.dropbox.com/s/6662pmgc9704raa/SkySounds3_5.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h2>Card V:</h2>
    </div>
    <div class="item__description">
      <p>A shining mirror, a portal to dimensions beyond, reflecting the mysteries of the multiverse. A gateway to realms unknown, a glimpse into the infinite, a portal to the unknown. A window to the soul, a mirror to the mind, a gateway to the beyond, a reflection of the self. A shining mirror, a bridge between worlds, a connection to the infinite, a journey through the unknown.  nwonknu eht hguorht yenruoj a ,etinifni eht ot noitcennoc a ,sdlrow neewteb egdirb a ,rorrim gninihs A .fles eht fo noitcelfer a ,dnoyeb eht ot yawetag a ,dnim eht ot rorrim a ,luos eht ot wodniw A .nwonknu eht ot latrop a ,etinifni eht otni espmilg a ,nwonknu smlaer ot yawetag A .esrevinu eht fo seiretsym eht gnitcelfer ,dnoyeb snoisnemid ot latrop a ,rorrim gninihs A. 
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