---
metaDescription: RasPi in die FH
date: 2022-04-30
permalink: /raspi-vpn/index.html
comments: false
eleventyNavigation:
  order: 10
  key: RaspiVPN
  title: Raspberry Pi VPN in die FH
  parent: FH
---

# Raspberry Pi VPN Setup in die FH

Test Test

Test Obsidian links [test](test.md)

[home](../home.md)

![Bildschirmfoto 2022-04-30 um 00.43.45 1.png](../../images/Bildschirmfoto%202022-04-30%20um%2000.43.45%201.png)
So gehts leider nicht mit dem Spacebook Template (das ist von Obsidian-export):

````
![Bild](Bild)
````

![test-screenshot.png](test-screenshot.png)

Es muss immer der Pfad dabei sein:

````
![Bild](content/images/Bild)
````

aber wenn das Bild zu groß ist lieber gleich Eleventy Image Plugin verwenden

````
{% image "test-screenshot.png" "Test" "200px" %}
````

{% image "test-screenshot.png" "Test" "200px" %}
