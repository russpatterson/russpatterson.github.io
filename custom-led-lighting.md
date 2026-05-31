---
layout: default
title: Custom LED Lighting
permalink: /custom-led-lighting/
---

# Custom LED Lighting

For a stretch of years, my electronics hobby turned into a serious custom lighting business. I designed and built high-power LED fixtures, controller boards, power electronics, switching systems, and software-controlled patterns for real installations.

This work started with experiments in solar power, battery chargers, microcontrollers, custom circuit boards, and high-power LEDs. I was designing my own electronics and circuit boards, then having the boards manufactured in China so I could build the fixtures and controllers I wanted. It grew into paid installations where the lights had to survive real heat, real power, real deadlines, and real buildings.

<style>
  .led-hero {
    display: grid;
    gap: 20px;
    grid-template-columns: minmax(0, 1.1fr) minmax(260px, 0.9fr);
    margin: 24px 0;
  }

  .led-hero img,
  .led-feature img,
  .led-card img {
    border-radius: 8px;
    display: block;
    width: 100%;
  }

  .led-panel {
    background: #f7f7f7;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 16px 18px;
  }

  .led-grid {
    display: grid;
    gap: 18px;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    margin: 24px 0;
  }

  .led-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    background: #fff;
  }

  .led-card h2 {
    font-size: 1.1rem;
    margin: 0 0 8px;
  }

  .led-card div,
  .led-card p {
    margin: 0;
  }

  .led-card div {
    padding: 14px 16px 16px;
  }

  .led-card > p {
    padding: 12px 14px 14px;
  }

  .led-card img {
    aspect-ratio: 4 / 3;
    object-fit: cover;
  }

  .led-card.portrait img {
    aspect-ratio: 3 / 4;
  }

  .led-feature {
    margin: 24px 0;
  }

  .led-caption {
    color: #555;
    font-size: 0.92rem;
    margin-top: 8px;
  }

  @media (max-width: 720px) {
    .led-hero {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="led-hero">
  <div>
    <p>I was working right at the practical edge of what hobbyist-accessible LED technology could do at the time: heat paste, big heat sinks, lots of watts, custom boards, microcontrollers, and fixtures bright enough to throw color across the side of a building.</p>

    <p>The fun part was that the hobby paid for itself. The hard part was that paid lighting jobs meant real clients, real installs, and last-minute delivery pressure.</p>
  </div>
  <img src="/assets/images/LED_DEMO/the-bloc-public-purple-new.jpg" alt="The Bloc cube lit purple at night">
</div>

## What I Built

<div class="led-grid">
  <section class="led-card"><div><h2>Custom Control Boards</h2><p>Microcontroller-based boards, made for the specific fixtures and patterns each job needed.</p></div></section>
  <section class="led-card"><div><h2>High-Power Fixtures</h2><p>High-output LEDs mounted to serious heat sinks, with power and thermal design treated as first-class problems.</p></div></section>
  <section class="led-card"><div><h2>Power Electronics</h2><p>Switching, drivers, wiring, power distribution, MOSFET drivers, and the practical engineering needed to keep the lights alive.</p></div></section>
  <section class="led-card"><div><h2>Pattern Software</h2><p>Programmable colors, fades, pulses, and client-specific lighting behavior driven by embedded controllers.</p></div></section>
</div>

## The Bloc - Downtown Los Angeles

The largest thing I built was the internal lighting rig for the giant cube at The Bloc in downtown Los Angeles. The shopping center was being torn out and rebuilt, and the cube was used as a public signal that a major change was coming.

<div class="led-feature">
  <img src="/assets/images/LED_DEMO/the-bloc-downtown-la.jpg" alt="Downtown Los Angeles establishing shot for The Bloc project">
  <div class="led-caption">Downtown Los Angeles, where The Bloc cube installation lived.</div>
</div>

<div class="led-grid">
  <section class="led-card">
    <img src="/assets/images/LED_DEMO/the-bloc-night-street.jpg" alt="The Bloc cube seen from the street at night">
    <p>The cube from the street at night, announcing that the center was changing.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/the-bloc-purple-cube-close.jpg" alt="The Bloc cube glowing purple">
    <p>The exterior cube glowing purple.</p>
  </section>

  <section class="led-card portrait">
    <img src="/assets/images/LED_DEMO/the-bloc-russ-under-cube.jpg" alt="Russ Patterson standing under The Bloc cube">
    <p>Standing under the cube during the install.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/the-bloc-frame-white.jpg" alt="Internal LED frame inside The Bloc cube">
    <p>The custom frame inside the cube, with the LEDs and controllers visible.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/the-bloc-frame-blue-new.jpg" alt="Internal LED frame inside The Bloc cube glowing blue">
    <p>The internal frame and lighting hardware in blue.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/the-bloc-public-blue.jpg" alt="The Bloc cube glowing blue for the public">
    <p>What the public saw as the cube shifted through color states.</p>
  </section>
</div>

## AllSaints - Las Vegas Strip

This was the AllSaints clothing light on the Las Vegas Strip, next to the Bellagio fountains on the side of the Cosmopolitan. It was a goat-skull light that flickered like an Edison bulb. In the sea of Las Vegas lights it was a small circle in a huge field of brightness, but it is still there running after all these years: my hand-built, hand-wired, rock-solid, thermal-resistant design, with my code still 100 feet off the ground in Las Vegas, flickering lights every night. Part of me is out there in Las Vegas every night, pounding out the pulse of flickering lights that city runs on. The store is still visible as a real location on Google Maps: [AllSaints at The Cosmopolitan of Las Vegas](https://maps.app.goo.gl/rzw4NjHQd4u3ZhiT9).

<div class="led-feature">
  <img src="/assets/images/LED_DEMO/allsaints-cosmopolitan-las-vegas.jpg" alt="AllSaints goat skull light on the side of the Cosmopolitan in Las Vegas">
  <div class="led-caption">The AllSaints goat-skull light on the side of the Cosmopolitan, near the Bellagio fountains.</div>
</div>

## Solar Controller Product Work

Before the lighting work became the thing that made money, I was building solar power, battery-charging, and solar fountain controller projects. The North County Solar and Water controller work fed directly into the LED work: waterproof boxes, status LEDs, control boards, sensor inputs, and field-ready wiring.

<div class="led-grid">
  <section class="led-card">
    <img src="/assets/images/LED_DEMO/solar-fountain-controller-product.jpg" alt="North County Solar and Water solar fountain controller product">
    <p>A silkscreened waterproof solar fountain controller sample with buttons, status lights, and the North County Solar and Water logo.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/solar-led-controller-light-sensor.jpg" alt="Solar LED controller with light-sensitive plug-in">
    <p>A solar LED controller with a light-sensitive plug-in so it could know when it was nighttime.</p>
  </section>

  <section class="led-card portrait">
    <img src="/assets/images/LED_DEMO/solar-fountain-controller-panel.jpg" alt="Solar fountain controller panel and waterproof box on grass">
    <p>Solar controller hardware on the lawn: panel, waterproof box, and early control board.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/solar-controller-desk-lid.jpg" alt="Solar controller lid and board on electronics bench">
    <p>The controller lid, status LED, and board running on my electronics development desk.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/solar-led-controller-open-box.jpg" alt="Solar LED controller circuit board inside waterproof box">
    <p>Another view of the solar LED controller product with the circuit board inside the waterproof box.</p>
  </section>
</div>

## Boards, Silkscreening, And Fabrication

These projects were not just wiring LEDs together. I was routing jigs, doing silkscreen samples, cutting labels, machining waterproof boxes, testing board revisions, and building my own fixtures around the electronics.

<div class="led-grid">
  <section class="led-card">
    <img src="/assets/images/LED_DEMO/silkscreen-jig-sample.jpg" alt="Silkscreen sample and routed jig for controller boxes">
    <p>A silkscreen sample and the routed jig I made so the box artwork would line up correctly before sending the screen to the silkscreener.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/cutting-controller-labels.jpg" alt="Cutting controller labels and stickers">
    <p>Cutting labels and stickers for the controller boxes.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/machining-waterproof-boxes.jpg" alt="Machining waterproof boxes for LED hardware">
    <p>Machining waterproof boxes so the fixtures and controllers could mount cleanly.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/waterproof-boxes-machined.jpg" alt="Machined waterproof boxes for custom LED hardware">
    <p>Machined boxes ready for assembly.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/solar-controller-board-rev-01.jpg" alt="Early solar controller board revision used for LED work">
    <p>An earlier revision of my main solar controller board, still being used for LED work before I had a dedicated LED board.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/solar-controller-board-rev-02.jpg" alt="Early solar controller circuit board revision">
    <p>Another early board revision, before moving to the 20-pin MCU.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/solar-controller-board-in-box.jpg" alt="Solar controller board mounted in an enclosure">
    <p>The controller board mounted into a waterproof enclosure.</p>
  </section>
</div>

## Bench Tests, Drivers, And Early Fixtures

A lot of the work happened on the bench before it ever became an installation: heat sinks, LED optics, acrylic covers, silicone glue, waterproof boxes, custom boards, MOSFET drivers, and high-powered light with nowhere to go yet.

<div class="led-grid">
  <section class="led-card portrait">
    <img src="/assets/images/LED_DEMO/early-hotel-light-junction-box.jpg" alt="Early hotel LED light mounted in a junction box">
    <p>One of the first hotel lights, built into a waterproof box inside a larger junction box, with heat sinks and wiring packed into the enclosure.</p>
  </section>


  <section class="led-card portrait">
    <img src="/assets/images/LED_DEMO/heatsink-led-lenses.jpg" alt="LED heat sink and lens optics">
    <p>Heat sink hardware and LED lens optics used to shape wide or narrow beam patterns.</p>
  </section>

  <section class="led-card portrait">
    <img src="/assets/images/LED_DEMO/early-hotel-light-open-box.jpg" alt="Early hotel light open enclosure">
    <p>An early hotel fixture style, similar to the Sandcastle and Roberts hotel lights.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/early-hotel-light-circuit-board.jpg" alt="Circuit board inside an early hotel LED light">
    <p>The circuit board inside one of those early hotel fixtures.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/custom-three-channel-led-driver.jpg" alt="Custom three-channel LED driver with MOSFET transistors">
    <p>A custom three-channel LED driver with big MOSFET transistors handling the power switching.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/three-channel-driver-in-box.jpg" alt="Custom LED driver mounted inside an enclosure">
    <p>The same style of driver mounted inside an enclosure with the wiring in place.</p>
  </section>
</div>

## CityWalk / Panda Inn Controller

I also built a controller for a CityWalk project, likely Panda Inn at Universal CityWalk in Los Angeles. It was another practical embedded job: custom controller, enclosure, and a lot of field wiring that had to work in the real installation. The light itself was huge, probably a long band of in-light around 30 feet or so, with a lot of LEDs and a lot of power. One of the practical problems was current fading across the chain, so we had to tap power into certain points along the run and get the power distribution right while still preserving the fade inside the light.

<div class="led-feature">
  <img src="/assets/images/LED_DEMO/citywalk-panda-inn-controller.jpg" alt="CityWalk Panda Inn LED controller enclosure and wiring">
  <div class="led-caption">The CityWalk controller bundled up with the rest of the field wiring.</div>
</div>

## Sandcastle Inn - Pismo Beach

The boutique hotel work was a different kind of challenge: it had to look warm, polished, and finished for guests. Sandcastle Inn in Pismo Beach wanted a white and yellow lighting treatment. Similar fixtures were used for other boutique hotel projects, including the Roberts hotel work in Beverly Hills.

<div class="led-grid">
  <section class="led-card">
    <img src="/assets/images/LED_DEMO/sandcastle-inn-01.jpg" alt="Sandcastle Inn warm exterior lighting">
    <p>Warm white and yellow exterior lighting at Sandcastle Inn.</p>
  </section>

  <section class="led-card portrait">
    <img src="/assets/images/LED_DEMO/sandcastle-inn-02.jpg" alt="Sandcastle Inn yellow accent lighting">
    <p>Yellow accent lighting for the hotel exterior.</p>
  </section>
</div>

## Marina del Rey LED Installation

The blue and white bench-test photos below were for the Marina del Rey lights. I was testing the LEDs while the silicone-glued acrylic weather covers cured on the heat sinks, with all that high-power light burning color into the workbench before it had a building to wash across. There is also a video here: [Marina del Rey LED lights on YouTube](https://www.youtube.com/watch?v=jwejw5C9Zy8).

A fun story from that install: when we stayed there to check it out, the guy at the liquor store on the corner told me that sometimes homeless people would stand underneath those lights and pretend they were charging up.

<div class="led-feature">
  <img src="/assets/images/LED_DEMO/marina-del-rey-led.png" alt="Marina del Rey LED lighting installation video still">
  <div class="led-caption">Video still from the Marina del Rey LED lighting installation.</div>
</div>

<div class="led-grid">
  <section class="led-card">
    <img src="/assets/images/LED_DEMO/acrylic-lens-glow-test-02.jpg" alt="Marina del Rey LED bench test with acrylic weather covers">
    <p>Bench testing the Marina del Rey LEDs while silicone-glued acrylic weather covers cured on top of the heat sinks.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/acrylic-lens-glow-test-03.jpg" alt="Marina del Rey high-power LED bench test">
    <p>The intense blue and white glow from the Marina del Rey lights before they went into the field.</p>
  </section>
</div>

## Universal Studios Hollywood - Simpsons Nuclear Workstation

The biggest controller project was Homer Simpson's nuclear workstation at Universal Studios Hollywood. I have been a huge Simpsons fan since the Tracy Ullman Show shorts, so getting to work on this was a real career highlight. It was a six-channel interactive controller: when someone pushed the button, the installation went into meltdown mode, with lights, sirens, and shaking toxic waste barrels. I got to be part of a Homer Simpson meltdown gag that people from all over the world see every day.

<div class="led-grid">
  <section class="led-card">
    <img src="/assets/images/LED_DEMO/simpsons-shop-cutout-01.jpg" alt="Homer Simpson nuclear workstation shop cutout before installation">
    <p>Shop fabrication for the Homer Simpson nuclear workstation before it was installed and painted.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/simpsons-shop-cutout-02.jpg" alt="Simpsons workstation cutout before installation">
    <p>Another pre-install shop view of the workstation cutouts.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/simpsons-shop-cutout-03.jpg" alt="Simpsons workstation cutout and shop assembly">
    <p>The workstation parts before they became part of the finished themed environment.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/simpsons-workstation-01.jpg" alt="Universal Studios Simpsons nuclear workstation exterior">
    <p>The Simpsons nuclear workstation installation at Universal Studios Hollywood.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/simpsons-workstation-04.jpg" alt="Simpsons nuclear workstation panels and buttons">
    <p>The workstation surface, with the interactive controls that triggered meltdown mode.</p>
  </section>

  <section class="led-card">
    <img src="/assets/images/LED_DEMO/simpsons-workstation-07.jpg" alt="Simpsons nuclear workstation barrels and warning door">
    <p>The toxic waste barrels and warning door that were part of the triggered show effect.</p>
  </section>
</div>

## Hardware And Parts

<div class="led-feature">
  <img src="/assets/images/LED_DEMO/led-hardware-parts.jpg" alt="Custom LED fixture hardware parts">
  <div class="led-caption">Fixture hardware and parts from the build process.</div>
</div>

## Why It Matters

This was not my main career track, but it reached a professional level. Alongside video games and technical leadership, it is another example of building real systems from scratch: hardware, software, power, thermal behavior, fabrication, installation, and client delivery.

<div class="led-panel">
  I will add more photos, build notes, board shots, and project stories here as I collect the old material.
</div>