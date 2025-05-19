---
layout: default
title: "Skateparks within 150 Miles of Dunedin, FL"
description: "A comprehensive guide to skateparks in Florida within 150 miles of Dunedin"
---

# Skateparks within 150 Miles of Dunedin, FL

<p class="intro-text">This page contains information about skateparks near Dunedin, FL</p>

<div class="skatepark-container">

{% for park in site.data.parks %}

<div class="park-card">
  <h2>🛹 {{ park.name }}</h2>
  <ul>
    <li><strong>Location:</strong> {{ park.location }}</li>
    <li><strong>Distance from Dunedin:</strong> {{ park.distance }}</li>
    <li><strong>Builder:</strong> {{ park.builder }}</li>
    <li><strong>Features:</strong> {{ park.features }}</li>
    <li><strong>Indoor/Outdoor:</strong> {{ park.indoor_outdoor }}</li>
    <li><strong>Public/Private:</strong> {{ park.public_private }}</li>
    <li><strong>Status:</strong> <span class="status-{{ park.status_class }}">{{ park.status }}</span></li>
    <li><strong>Shaded:</strong> {{ park.shade }}</li>
    <li><strong>Webpage:</strong> <a href="{{ park.url }}">{{ park.webpage }}</a></li>
  </ul>
</div>
{% endfor %}

<!-- Alternative layout if Liquid templating doesn't work -->

<div class="park-card">
  <h2>🛹 688 Skate Park – Clearwater, FL</h2>
  <ul>
    <li><strong>Location:</strong> 6140 Ulmerton Road, Clearwater, FL 33760</li>
    <li><strong>Distance from Dunedin:</strong> ~10 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks</li>
    <li><strong>Features:</strong> Indoor wooden park with multiple ramps and street elements.</li>
    <li><strong>Indoor/Outdoor:</strong> Indoor</li>
    <li><strong>Public/Private:</strong> Private</li>
    <li><strong>Status:</strong> <span class="status-closed">Closed</span></li>
    <li><strong>Shaded:</strong> Yes (fully indoor facility)</li>
    <li><strong>Webpage:</strong> <a href="https://teampain.com/projects/688-skate-park/">Team Pain – 688 Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Alachua Skate Park (Hal Brady Recreation Complex) – Alachua, FL</h2>
  <ul>
    <li><strong>Location:</strong> 14300 NW 146th Terrace, Alachua, FL 32615</li>
    <li><strong>Distance from Dunedin:</strong> ~116 miles</li>
    <li><strong>Builder:</strong> Unknown (prefabricated ramps)</li>
    <li><strong>Features:</strong> Modular ramps, decks, rails, and boxes for all skill levels</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Alachua) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (renovated and reopened in 2025)</li>
    <li><strong>Shaded:</strong> Partially (open area; some shade from nearby structures/trees)</li>
    <li><strong>Webpage:</strong> <a href="https://www.cityofalachua.com/government/recreation-culture/parks/hal-brady-recreation-skate-park">City of Alachua Recreation – Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Apollo Beach Skate Park – Apollo Beach, FL</h2>
  <ul>
    <li><strong>Location:</strong> 664 Golf and Sea Blvd, Apollo Beach, FL 33572</li>
    <li><strong>Distance from Dunedin:</strong> ~34 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks</li>
    <li><strong>Features:</strong> 11,000 sq.ft. concrete park with a unique three-pointed "sun" layout featuring artistic acid-stained concrete and brick patterns. Obstacles include a step-up, rock gap, multiple ledges and stairs with handrails, three granite elements (bench, ledge, and ledge wall), a jersey barrier, quarter pipe with hip, large bank, and a radius launch kicker. No bowl (street plaza style).</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (Hillsborough County) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (opened 2012)</li>
    <li><strong>Shaded:</strong> Limited (open concrete; minimal tree shade, though features are themed for sun imagery)</li>
    <li><strong>Webpage:</strong> <a href="https://hcfl.gov/locations/apollo-beach-skate-park">Hillsborough County – Apollo Beach Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Apopka Skatepark – Apopka, FL</h2>
  <ul>
    <li><strong>Location:</strong> 101 N Forest Avenue, Apopka, FL 32703 (behind the Fran Carlton Center)</li>
    <li><strong>Distance from Dunedin:</strong> ~90 miles</li>
    <li><strong>Builder:</strong> Pivot Custom Skateparks</li>
    <li><strong>Features:</strong> Small concrete street-oriented park with a variety of ledges and rails. Includes movable smaller ramps/boxes for creative setups. No large bowl or vert – geared toward street skating.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Apopka) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (newer park, opened circa 2022)</li>
    <li><strong>Shaded:</strong> Limited (no roof; no lights for night use)</li>
    <li><strong>Webpage:</strong> <a href="https://www.apopka.gov/Facilities/Facility/Details/Apopka-Action-Sports-Park-32">City of Apopka – Apopka Action Sports Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Bayhead Action Park – Largo, FL</h2>
  <ul>
    <li><strong>Location:</strong> 375 Seminole Blvd, Largo, FL 33770</li>
    <li><strong>Distance from Dunedin:</strong> ~11 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (design/build collaboration, ~2008)</li>
    <li><strong>Features:</strong> 7,000 sq.ft. concrete skatepark with a 5' deep bowl and surrounding street elements. Banks, transitions, and rails are present in a compact layout. Lighted for evening use. (Also part of a park complex with sports courts and a dog park.)</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Largo) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Minimal (open concrete, but sessions possible at night under lights)</li>
    <li><strong>Webpage:</strong> <a href="https://www.largo.com/facility_detail_T64_R30.php">City of Largo – Bayhead Action Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Bethune Point Skatepark – Daytona Beach, FL</h2>
  <ul>
    <li><strong>Location:</strong> 11 Bellevue Ave, Daytona Beach, FL 32114</li>
    <li><strong>Distance from Dunedin:</strong> ~135 miles</li>
    <li><strong>Builder:</strong> Spohn Ranch (design-build, opened 2009)</li>
    <li><strong>Features:</strong> 16,000 sq.ft. waterfront concrete park with a distinctive modern plaza and a replica backyard pool bowl (with blue tile and pool coping). Notable centerpiece is the "Broken Pyramid" skateable sculpture in the lower plaza, integrated with LED lighting. The park has stairs, rails, ledges, banks, and transitions arranged with aesthetic symmetry.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Daytona Beach) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (graffiti repainting and maintenance done in 2024)</li>
    <li><strong>Shaded:</strong> Limited (open-air; some shade in spectator areas, none over ramps)</li>
    <li><strong>Webpage:</strong> <a href="https://daytonabeach.gov/1186/Bethune-Point-Park-Skateboard-Park">City of Daytona Beach – Bethune Point Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Bonita Springs Skatepark – Bonita Springs, FL</h2>
  <ul>
    <li><strong>Location:</strong> Bonita Springs Recreation Center, Bonita Springs, FL</li>
    <li><strong>Distance from Dunedin:</strong> ~130 miles</li>
    <li><strong>Builder:</strong> New Line Skateparks FL Inc</li>
    <li><strong>Features:</strong> Concrete skatepark and pump track.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Not specified</li>
    <li><strong>Webpage:</strong> <a href="https://www.newlineskateparks.com/project/bonita-springs-skatepark/">New Line Skateparks – Bonita Springs Skatepark</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Bradenton Riverwalk Skatepark – Bradenton, FL</h2>
  <ul>
    <li><strong>Location:</strong> 101 Waterfront Dr, Bradenton, FL 34205</li>
    <li><strong>Distance from Dunedin:</strong> ~38 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2012)</li>
    <li><strong>Features:</strong> 15,000 sq.ft. concrete park partially under a highway bridge for shade. Has a multi-section design: a large pool bowl with tile and pool coping, a smaller flow "mini-bowl" with a vert wall, and an extensive street plaza. Street obstacles include multiple ledges, stairs with rails, hips, manual pads, and even a skateable Jersey barrier and a piece of real railroad track as a rail. Integrated "moguls" and banks provide flow. Free public Wi-Fi and nighttime lighting are available (park is popular for night sessions).</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (Bradenton Riverwalk) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Yes (partially by the bridge structure, providing relief from sun/rain over a section of the park)</li>
    <li><strong>Webpage:</strong> <a href="https://teampain.com/projects/bradenton-riverwalk-skatepark/">Bradenton Riverwalk Skatepark info</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Brandon Skate Park at Providence East (Providence Skatepark) – Riverview, FL</h2>
  <ul>
    <li><strong>Location:</strong> 5720 Providence Rd, Riverview, FL 33578 (Greater Brandon area)</li>
    <li><strong>Distance from Dunedin:</strong> ~32 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2012)</li>
    <li><strong>Features:</strong> 14,500 sq.ft. concrete park with a mix of street and transition. Noted for its Dogtown-era inspired vert bowls/pools – including a concrete bowl/pool with pool coping and tiles – and a modest street course with ramps and rails. Elements include a 6' corner quarter pipe, an A-frame funbox, hubba ledges, stair sets, rails, and a spacious flow section. Helmets and waivers required (staffed facility).</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor (fenced skatepark within a county park)</li>
    <li><strong>Public/Private:</strong> Public (Hillsborough County) – free admission, staffed during set hours</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Minimal (open concrete, but there are small shade shelters/benches)</li>
    <li><strong>Webpage:</strong> <a href="https://hcfl.gov/locations/providence-skate-park">Hillsborough County – Providence Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Candyland Skatepark – Longwood, FL</h2>
  <ul>
    <li><strong>Location:</strong> 599 Longdale Ave (Candyland Park), Longwood, FL 32750</li>
    <li><strong>Distance from Dunedin:</strong> ~105 miles</li>
    <li><strong>Builder:</strong> Unknown (likely modular/prefab elements)</li>
    <li><strong>Features:</strong> A community skate spot within Candyland Park. Small outdoor skatepark with movable metal ramps, a mini half-pipe, quarter pipes, and rails. In 2021 a new pump-track was added adjacent to the skate area. The ramps are beginner-friendly; the park is bike-friendly and encourages creative rearrangement of obstacles. Efforts have been made to expand and improve this park via grants.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Longwood) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> No roof; limited tree shade. (There is an adjacent covered pavilion in the park, but the skatepad itself is unshaded)</li>
    <li><strong>Webpage:</strong> <a href="https://longwoodfl.org/Facilities/Facility/Details/Candyland-Sports-Complex-4">City of Longwood – Candyland Sports Complex</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Carrollwood Village Skatepark – Tampa, FL</h2>
  <ul>
    <li><strong>Location:</strong> Carrollwood Village Park, Tampa, FL</li>
    <li><strong>Distance from Dunedin:</strong> ~25 miles</li>
    <li><strong>Builder:</strong> Spohn Ranch Skateparks</li>
    <li><strong>Features:</strong> 7,000 sq.ft. concrete park with a blend of modern concrete pump track and traditional skatepark elements including stairs, ledges, and a mini half-pipe.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (opened in 2020)</li>
    <li><strong>Shaded:</strong> Not specified</li>
    <li><strong>Webpage:</strong> <a href="https://www.spohnranch.com/portfolio/carrollwood-skatepark/">Spohn Ranch – Carrollwood Village Skatepark</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Deputy Brandon Coates Skate Park – Orlando, FL (South Chase)</h2>
  <ul>
    <li><strong>Location:</strong> 3815 Substation Road, Orlando, FL 32837</li>
    <li><strong>Distance from Dunedin:</strong> ~85 miles</li>
    <li><strong>Builder:</strong> Grindline Skateparks (opened 2021)</li>
    <li><strong>Features:</strong> A modern concrete skatepark about 8,000 sq.ft., built as part of Deputy Brandon Coates Community Park. It features a flow bowl and a street section with banks, ledges, rails, and a quarter pipe. The park's design caters to both beginners and advanced skaters, but is somewhat narrow in parts. Built in memory of a fallen deputy, it has become a community hub for local skaters.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (Orange County Parks) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (opened late 2021)</li>
    <li><strong>Shaded:</strong> Minimal (open-air; some shade in the late afternoon from surrounding trees)</li>
    <li><strong>Webpage:</strong> <a href="https://www.ocfl.net/cultureparks/parks.aspx?d=110&m=dtlvw">Orange County Parks – Deputy Brandon Coates Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Dunedin Stirling Skate Park – Dunedin, FL</h2>
  <ul>
    <li><strong>Location:</strong> 550 Laura Lane, Dunedin, FL 34698 (at MLK Jr. Recreation Center)</li>
    <li><strong>Distance from Dunedin:</strong> 0 miles (in-city)</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks</li>
    <li><strong>Features:</strong> 10,500 sq.ft. concrete park featuring a variety of transitions and street obstacles. Includes a medium-size bowl and vert quarter, banked hips, ledges, rails, and funboxes. Flow-oriented design allows continuous lines. The park is unsupervised, ride-at-your-own-risk and popular with skateboarders and scooter riders alike. Full pads recommended; helmet required for minors.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Dunedin) – small admission fee or membership may apply (city recreation facility)</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Partial (open concrete, but the park is surrounded by palm trees and adjacent to a building that provides some shade at edges)</li>
    <li><strong>Webpage:</strong> <a href="https://www.dunedingov.com/Activities-and-Recreation/Parks-Recreation/Recreation-Facilities/Stirling-Skate-Park">City of Dunedin – Stirling Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Eagle Skate Park – Cape Coral, FL</h2>
  <ul>
    <li><strong>Location:</strong> 315 SW 2nd Ave, Cape Coral, FL 33991 (adjacent to William "Bill" Austen Youth Center)</li>
    <li><strong>Distance from Dunedin:</strong> ~108 miles</li>
    <li><strong>Builder:</strong> American Ramp Company (ARC)</li>
    <li><strong>Features:</strong> One of the largest skate facilities in Southwest Florida at nearly 27,000 sq.ft. Equipped with a full array of ARC modular ramps, rails, spines, and a half-pipe. Also features a bowl. It caters to skateboards, scooters, and BMX (specific sessions for bikes) and is supervised by skate attendants. Amenities include a pro-shop, covered pavilion, restrooms, lights, sound system, and concessions (even ice cream). Helmets and waivers required; rentals available.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor (fenced, with some covered seating areas)</li>
    <li><strong>Public/Private:</strong> Public (City of Cape Coral) – admission fee required (daily or membership)</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Partially – There is an 800 sq.ft. covered pavilion for shade and some obstacles under it, but the main skate surface is open. Evening sessions under lights are popular.</li>
    <li><strong>Webpage:</strong> <a href="https://www.capecoral.gov/department/parks_and_recreationhome/eagles_skate_park/index.php">Cape Coral – Eagle Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Englewood Skatepark (J.M. Berlin Rotary Skatepark) – Englewood, FL</h2>
  <ul>
    <li><strong>Location:</strong> 6791 San Casa Dr, Englewood, FL 34224 (Ann & Chuck Dever Regional Park)</li>
    <li><strong>Distance from Dunedin:</strong> ~75 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2013)</li>
    <li><strong>Features:</strong> 18,000 sq.ft. concrete skatepark featuring two bowls (including a beginner-friendly bowl and an advanced bowl with pool coping) and an extensive street/plaza section. Obstacles include China bank-style ramps, stair sets, hubba ledges, rails, a flow section, and transition elements for all levels. Design is modern and smooth, suitable for both street and transition skaters. The park allows BMX on specified days (e.g. Tuesdays) and is free to use. Helmets required.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor (fenced park, staffed certain hours)</li>
    <li><strong>Public/Private:</strong> Public (Charlotte County) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (closed on Wednesdays; hours vary by season)</li>
    <li><strong>Shaded:</strong> Minimal (open concrete, some shade from trees around the perimeter; no roof over the park)</li>
    <li><strong>Webpage:</strong> <a href="https://www.charlottecountyfl.gov/departments/community-services/recreation-pools/skate-parks.stml">Charlotte County – Ann Dever Park Skatepark Info</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 FishHawk Ranch Skatepark – Lithia, FL</h2>
  <ul>
    <li><strong>Location:</strong> FishHawk Ranch, Lithia, FL</li>
    <li><strong>Distance from Dunedin:</strong> ~50 miles</li>
    <li><strong>Builder:</strong> Spohn Ranch Skateparks</li>
    <li><strong>Features:</strong> Contemporary concrete skatepark and pump track.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Not specified</li>
    <li><strong>Webpage:</strong> <a href="https://www.spohnranch.com/construction-begins-on-new-fishhawk-ranch-skatepark-2019-08-08/">Spohn Ranch – FishHawk Ranch Skatepark</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Gainesville – Possum Creek Skatepark – Gainesville, FL</h2>
  <ul>
    <li><strong>Location:</strong> 4009 NW 53rd Ave, Gainesville, FL 32653 (Possum Creek Park)</li>
    <li><strong>Distance from Dunedin:</strong> ~116 miles</li>
    <li><strong>Builder:</strong> Spohn Ranch (opened 2010)</li>
    <li><strong>Features:</strong> 18,000 sq.ft. concrete park, considered one of Florida's premier skate landscapes. The park is triangular in layout and offers a multi-level bowl plus modern plaza elements integrated with landscaping. Features include ledges, rails, banks, gaps, and a flow bowl, all arranged with aesthetic symmetry. A "real urban environment" feel is created with landscaping that doubles as skate elements and stormwater management. Lights were added for night skating, making it a popular spot for evening sessions. All wheels are welcome (skateboards, inline, BMX), and pads are recommended.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Gainesville) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Partially – open sky overhead, but integrated shade elements: the park's design includes trees and landscaping inside the skate area providing some shade.</li>
    <li><strong>Webpage:</strong> <a href="https://www.gainesvillefl.gov/Parks/Possum-Creek-Park">City of Gainesville – Possum Creek Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Golgotha Skate Park (Calvary Chapel) – Pinellas Park, FL</h2>
  <ul>
    <li><strong>Location:</strong> 8900 US Hwy 19 N, Pinellas Park, FL 33782 (Calvary Chapel St. Petersburg campus)</li>
    <li><strong>Distance from Dunedin:</strong> ~13 miles</li>
    <li><strong>Builder:</strong> Church volunteers (wood/metal ramps)</li>
    <li><strong>Features:</strong> A private indoor/outdoor hybrid facility operated by a church ministry. Consists of a covered pavilion with wooden ramps and obstacles tailored for beginner and intermediate skaters. Includes quarter pipes, a small mini-ramp, funbox, and rails in a warehouse-style setup. Also adjacent is a rec room with indoor games (basketball, ping-pong, etc.) for youth. Emphasis is on a positive atmosphere. Helmets and waivers are required for all participants.</li>
    <li><strong>Indoor/Outdoor:</strong> Indoor (in a gymnasium) – with open-air sides</li>
    <li><strong>Public/Private:</strong> Private (non-profit) – Open to public during specific hours, free of charge (limited sessions weekly: Sunday afternoons and one weeknight)</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (operates on limited schedule)</li>
    <li><strong>Shaded:</strong> Yes – fully roofed facility (shade and weather protection)</li>
    <li><strong>Webpage:</strong> <a href="https://calvarystp.org/skatepark/">Calvary Chapel St. Petersburg – Skate Park Ministry</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Ian Tilmann Skatepark – Safety Harbor, FL</h2>
  <ul>
    <li><strong>Location:</strong> 940 7th St S, Safety Harbor, FL 34695 (in Safety Harbor City Park)</li>
    <li><strong>Distance from Dunedin:</strong> ~6 miles</li>
    <li><strong>Builder:</strong> Pour-it-Yourself (modular prefab elements)</li>
    <li><strong>Features:</strong> A small neighborhood skatepark named in memory of local skater Ian Tilmann. Features a concrete/asphalt pad with prefab ramps: quarter pipes, a funbox with rails, a mini halfpipe, and some ledges. Despite its small size, it's regarded as a fun spot for local skaters "for it being so little". Open 7 AM – 10 PM daily under lights. Located in a mixed-use park (playground, dog park, etc.).</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Safety Harbor) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Minimal (few shade trees around; park lights for night skating)</li>
    <li><strong>Webpage:</strong> <a href="https://www.cityofsafetyharbor.com/964/Safety-Harbor-City-Park">City of Safety Harbor – City Park info</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Jackson Springs Skatepark – Town 'n' Country (Tampa), FL</h2>
  <ul>
    <li><strong>Location:</strong> 8620 Jackson Springs Rd, Tampa, FL 33615</li>
    <li><strong>Distance from Dunedin:</strong> ~17 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2017)</li>
    <li><strong>Features:</strong> A 13,000+ sq.ft. concrete park featuring a vert sections and flow bowl along with a street plaza. Notable for its large vert bowl with pool coping (one of the few in the Tampa area) and a beginner-friendly flow section. The street area has stairs, handrails, hubba ledges, quarter-pipes, and banks. The park was designed with community input and has become a local favorite. Fenced and supervised during certain hours; helmets required under 18.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (Hillsborough County) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Limited (no roof; a few shade canopies/trees at the perimeter, and lights for night use)</li>
    <li><strong>Webpage:</strong> <a href="https://hcfl.gov/locations/jackson-springs-skate-park">Hillsborough County – Jackson Springs Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Kissimmee Skate Park (Mark Durbin Park at Lakeside) – Kissimmee, FL</h2>
  <ul>
    <li><strong>Location:</strong> 2253 Lakeside Dr, Kissimmee, FL 34743</li>
    <li><strong>Distance from Dunedin:</strong> ~85 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (2009); expanded 2014</li>
    <li><strong>Features:</strong> A medium-sized outdoor concrete skatepark featuring a variety of street obstacles (ramps, rails, ledges) and a small bowl. The park is lit at night and unsupervised (ride at your own risk). It caters to all levels with a two-tier design: an upper plaza and a lower street course with bank ramps and grind ledges. Adjacent to a roller-hockey rink and other park amenities.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Kissimmee) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Minimal (open concrete, though there are shade pavilions in the park nearby)</li>
    <li><strong>Webpage:</strong> <a href="https://www.kissimmee.gov/government/departments/parks-recreation/parks-facilities/mark-durbin-community-park-at-lakeside">City of Kissimmee – Mark Durbin Community Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Lake Mary Skatepark (Trailblazer Park) – Lake Mary, FL</h2>
  <ul>
    <li><strong>Location:</strong> 550 Rantoul Lane, Lake Mary, FL 32746</li>
    <li><strong>Distance from Dunedin:</strong> ~95 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2013)</li>
    <li><strong>Features:</strong> 10,000 sq.ft. concrete park featuring a balance of street and transition. Includes a medium kidney bowl (smooth transitions), a snake-run style flow section, and a street plaza with stairs, rails, hubbas, euro-gap, quarter-pipes and banks. Lights on site allow for night sessions. The design makes good use of limited space, though the layout is linear. No pads required; unsupervised.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Lake Mary) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Partial (no roof, but there are two small shade shelters inside the skate area and some surrounding trees)</li>
    <li><strong>Webpage:</strong> <a href="https://www.lakemaryfl.com/parks-recreation/page/trailblazer-park">City of Lake Mary – Skate Park Facility</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Lakeland Skate Park at Fletcher Park (Lake Bonny) – Lakeland, FL</h2>
  <ul>
    <li><strong>Location:</strong> 800 US-98 South, Lakeland, FL 33801</li>
    <li><strong>Distance from Dunedin:</strong> ~50 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2013)</li>
    <li><strong>Features:</strong> A 24,000 sq.ft. concrete skatepark divided into 4 main areas. Notably includes a large flow bowl, a pool-style bowl, a beginner bowl, and a spacious street plaza. The street section has multiple stair sets with handrails, granite ledges, banks, and a centerpiece pyramid. Transitions of varying sizes ring the park, allowing continuous flow. The park is unsupervised and open daily from 10 AM to 8 PM. No bikes allowed (skateboards/inline/scooters only).</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Lakeland) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Limited (some large trees around the park provide patches of shade on the concrete; otherwise open. The park is lighted for evening use).</li>
    <li><strong>Webpage:</strong> <a href="https://www.lakelandgov.net/departments/parks-recreation/parks/lake-bonny-park/">City of Lakeland – Skate Park @ Fletcher Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Lehigh Acres Skate Park (Veterans Park) – Lehigh Acres, FL</h2>
  <ul>
    <li><strong>Location:</strong> 55 Homestead Rd S, Lehigh Acres, FL 33936</li>
    <li><strong>Distance from Dunedin:</strong> ~120 miles</li>
    <li><strong>Builder:</strong> Unknown (American Ramp Company prefab)</li>
    <li><strong>Features:</strong> A fenced concrete slab with a collection of prefabricated ramps and rails. Includes a medium half-pipe, quarter pipes, bank ramps, a funbox with hubba ledges and rail, and a spine. Layout is open and beginner-friendly. The park is part of Veterans Park Recreation Center and is popular with local youth. Lights are present for night use. Helmets recommended; unsupervised.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (Lee County) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (daily, during park hours)</li>
    <li><strong>Shaded:</strong> No overhead shade on the skatepad (adjacent park areas have pavilions)</li>
    <li><strong>Webpage:</strong> <a href="https://www.leegov.com/parks/facility?fid=0072">Lee County – Veterans Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Loyce E. Harpe Park Skatepark – Mulberry, FL</h2>
  <ul>
    <li><strong>Location:</strong> 300 W Carter Rd, Mulberry, FL 33860</li>
    <li><strong>Distance from Dunedin:</strong> ~60 miles</li>
    <li><strong>Builder:</strong> Spohn Ranch Skateparks</li>
    <li><strong>Features:</strong> Concrete skatepark with various street and transition elements.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Not specified</li>
    <li><strong>Webpage:</strong> <a href="https://www.spohnranch.com/a-turnkey-design-build-for-new-skatepark-in-polk-county-florida-2021-04-08/">Spohn Ranch – Loyce E. Harpe Park Skatepark</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Marina Park Skateboard Park – Titusville, FL</h2>
  <ul>
    <li><strong>Location:</strong> 501 Marina Rd, Titusville, FL 32796</li>
    <li><strong>Distance from Dunedin:</strong> ~130 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2014)</li>
    <li><strong>Features:</strong> A concrete skatepark of roughly 12,000 sq.ft. on the Indian River waterfront. It has a mix of street features (stairs, rails, grind boxes) and small transitions. A standout feature is a medium-sized bowl with extensions. The park's design incorporates the riverfront setting (views of the water). Generally suited for beginner to intermediate skaters. Helmets required for under 18.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Titusville) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Minimal (open to sun; breezes off the water help, but little structural shade)</li>
    <li><strong>Webpage:</strong> <a href="https://www.titusville.com/Facilities/Facility/Details/Marina-Park-14">City of Titusville – Marina Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 New Smyrna Beach Skatepark (NSB Skate Park) – New Smyrna Beach, FL</h2>
  <ul>
    <li><strong>Location:</strong> 245 Industrial Park Ave, New Smyrna Beach, FL 32168</li>
    <li><strong>Distance from Dunedin:</strong> ~130 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2018)</li>
    <li><strong>Features:</strong> 8,500 sq.ft. concrete park split between a flow bowl and a street section. The flow bowl has multiple depths and extensions for carving and airs. The street area offers stairs, rails, quarter-pipes, banks, and ledges. There is also a separate vertical wall/extension popular in contests. The facility is staffed and has set hours (typically noon–8pm daily). Helmets and signed waivers required; small entry fee may apply for non-residents.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor (fenced, with on-site staff building)</li>
    <li><strong>Public/Private:</strong> Public (City of New Smyrna Beach) – nominal fee for entry (resident discounts)</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> No roof over the park (sun exposure), but some shade at the spectator areas and an on-site gazebo. No lights at night (closes at dusk typically).</li>
    <li><strong>Webpage:</strong> <a href="https://www.cityofnsb.com/Facilities/Facility/Details/NSB-Skate-Park-30">City of New Smyrna Beach – NSB Skate Park info</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 North Port Skate Park – North Port, FL</h2>
  <ul>
    <li><strong>Location:</strong> 5651 North Port Blvd, North Port, FL 34287</li>
    <li><strong>Distance from Dunedin:</strong> ~83 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2012)</li>
    <li><strong>Features:</strong> 14,000 sq.ft. concrete park comprised of multiple bowls and a street course. There is a large multi-section bowl with differing depths and a spine/volcano in the middle, as well as a smaller shallow bowl. The street area has ramps, ledges, rails and a quarter-pipe. The park also features two small shade shelters and vending on site. Restrooms available nearby. Pads recommended; unsupervised (dawn to 8 PM).</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of North Port) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Partially – two small covered shelters on the skate deck for shade; the skating surface itself is largely unshaded.</li>
    <li><strong>Webpage:</strong> <a href="https://www.cityofnorthport.com/government/city-services/parks-recreation/parks-facilities/skate-park">City of North Port – Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Ocala Skate Park – Ocala, FL (Tuscawilla Park)</h2>
  <ul>
    <li><strong>Location:</strong> 800 NE 8th Ave, Ocala, FL 34470</li>
    <li><strong>Distance from Dunedin:</strong> ~89 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2019)</li>
    <li><strong>Features:</strong> Currently a 10,000 sq.ft. concrete street course featuring banks, quarter-pipes, stairs, rails, and ledges. Designed as a modern plaza for street skating. Notably, no bowl yet – the park opened as street-only, but a 5,000 sq.ft. expansion (including bowls/ramps) was approved in 2025. The expansion/renovation is slated to add a flow bowl and additional transition features to make it a more all-around park. During construction, portions of the park may close. The park has murals, benches, and is 6 acres in total park size. Helmets required under 18.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Ocala) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (Expansion Under Construction) – (open for street section; new sections ETA late 2025).</li>
    <li><strong>Shaded:</strong> Minimal (open plaza; some shade from nearby trees). Post-expansion, additional shade structures may be included.</li>
    <li><strong>Webpage:</strong> <a href="https://www.ocalafl.org/government/city-departments-i-z/recreation-parks/parks/skate-park">City of Ocala – Ocala Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Orlando Skate Park (OSP) – Orlando, FL</h2>
  <ul>
    <li><strong>Location:</strong> 400 Festival Park Ave, Orlando, FL 32803</li>
    <li><strong>Distance from Dunedin:</strong> ~92 miles</li>
    <li><strong>Builder:</strong> Site Design Group (opened 2005; renovated 2013)</li>
    <li><strong>Features:</strong> A 17,000 sq.ft. outdoor concrete skatepark with diverse terrain. It boasts an expansive flow course with quarter-pipes and banks that connect to a street plaza (stair sets, rails, ledges) and a vert bowl (approx 11' deep) with pool coping. Also on site is a smaller peanut-shaped bowl and a beginner area. The park is staffed and fenced. Helmets are required (all ages) and entry fees apply (daily or membership). Lights allow skating until 10 PM. OSP regularly hosts events and lessons, being a central hub for Orlando skaters.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Orlando) – entry fee ($4 session or monthly pass)</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (7 days a week, afternoon into evening)</li>
    <li><strong>Shaded:</strong> Partially – no roof, but there are large shade trees around the park's perimeter that offer some relief. Bleacher areas are covered.</li>
    <li><strong>Webpage:</strong> <a href="https://www.orlando.gov/Parks-the-Environment/Directory/Orlando-Skate-Park">City of Orlando – Orlando Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Palm Coast Skatepark (Ralph Carter Park) – Palm Coast, FL</h2>
  <ul>
    <li><strong>Location:</strong> 1385 Rymfire Dr, Palm Coast, FL 32164</li>
    <li><strong>Distance from Dunedin:</strong> ~144 miles</li>
    <li><strong>Builder:</strong> Spohn Ranch (original prefab park circa 2008)</li>
    <li><strong>Features:</strong> A small outdoor skatepark originally built on a concrete pad with prefab ramps. It includes quarter pipes, a mini halfpipe, funbox, spine, and flat rails. It's designed to be a well-rounded neighborhood skate spot, with "smaller and larger versions of ramps, spines, ledges, and quarter pipes sprinkled throughout the park," making it suitable for all levels. Lights are present for night skating – a standout feature in many reviews. The city has plans for a future concrete park, but as of now this facility is basic but loved by locals.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Palm Coast) – free admission</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (dawn to 10 PM)</li>
    <li><strong>Shaded:</strong> No built shade over the ramps (open air), but park has some trees adjacent and benches.</li>
    <li><strong>Webpage:</strong> <a href="https://www.palmcoastgov.com/parks/ralph-carter">Palm Coast – Ralph Carter Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Perry Harvey Sr. Skatepark "Bro Bowl 2.0" – Tampa, FL</h2>
  <ul>
    <li><strong>Location:</strong> 1200 N Orange Ave, Tampa, FL 33602 (Perry Harvey Sr. Park, downtown Tampa)</li>
    <li><strong>Distance from Dunedin:</strong> ~20 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2015, replacing the historic 1978 Bro Bowl)</li>
    <li><strong>Features:</strong> A 17,000 sq.ft. concrete park that pays homage to the original "Bro Bowl" while adding modern features. Bro Bowl 2.0 includes a replica of the old bowl (shallow snake-run style) plus extensive new street terrain: multiple ramps, stair sets, banks, ledges, and rails spread through a plaza. There's also a snake-run and quarter-pipes to retain flow. The park is free and open sunrise to sunset. As part of a city park, it has paths, artwork, and historical markers commemorating its legacy. No staff on site; popular with downtown skaters and BMXers.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Tampa) – free</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Partially – The park is open-air but features some large old oak trees around and within the skate area that provide patches of shade. Also, an overpass nearby casts some shade at certain times.</li>
    <li><strong>Webpage:</strong> <a href="https://www.tampa.gov/parks-and-recreation/parks/perry-harvey-sr-park">City of Tampa – Perry Harvey Park Skatepark</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Rippin' Riverside Skatepark – Oviedo, FL</h2>
  <ul>
    <li><strong>Location:</strong> 1600 Lockwood Blvd, Oviedo, FL 32765 (in Riverside Park)</li>
    <li><strong>Distance from Dunedin:</strong> ~110 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2015)</li>
    <li><strong>Features:</strong> 30,000 sq.ft. lighted skatepark – one of Central Florida's largest. It offers a California-style kidney pool with pool tile and coping, a flowing intermediate bowl/flow course, and a vast street plaza loaded with ledges, boxes, manual pads, stairs, and rails. There's also a vertical wall quarter and pump bumps. This park accommodates BMX on certain days and is staffed by Oviedo Parks (helmets required, small entry fee for non-residents). Night lighting allows skating until 10 PM.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Oviedo) – small fee for use (free for residents)</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> Minimal (open concrete, but has some adjacent shade canopies for spectators; the complex also includes a community center nearby)</li>
    <li><strong>Webpage:</strong> <a href="https://teampain.com/projects/riverside-skatepark-2/">City of Oviedo – Riverside Skate Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Ross Norton Skate Park – Clearwater, FL (Closed)</h2>
  <ul>
    <li><strong>Location:</strong> 1426 S Martin Luther King Jr. Ave, Clearwater, FL 33756 (Ross Norton Recreation Center)</li>
    <li><strong>Distance from Dunedin:</strong> ~6 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (renovated 2015)</li>
    <li><strong>Features:</strong> (Historical) This was a concrete and Skatelite park featuring a 4' half-pipe, funbox with rails, 6' spine, multiple quarter-pipes, and a bowl section – a good mix of street and transition. It was a beloved local spot, especially after a 2015 remodel that improved its flow. Demolition: As of March 2023, the park was demolished for an upcoming rebuild. Plans are underway to construct a new skatepark on the same site.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public</li>
    <li><strong>Status:</strong> Closed (demolished March 2023; new skatepark under construction)</li>
    <li><strong>Shaded:</strong> N/A (the new design will likely incorporate shade structures)</li>
    <li><strong>Webpage:</strong> <a href="https://www.stpeteparksrec.org/rossnorton.html">City of Clearwater – (Upcoming Skatepark Project)</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Sanctuary Skate Park – Punta Gorda (Charlotte County), FL</h2>
  <ul>
    <li><strong>Location:</strong> 6905 Florida St, Punta Gorda, FL 33950</li>
    <li><strong>Distance from Dunedin:</strong> ~83 miles</li>
    <li><strong>Builder:</strong> Rampage (prefab components)</li>
    <li><strong>Features:</strong> A basic outdoor skate facility within the South County Regional Park. It has a concrete slab with prefab ramps: quarter pipes at both ends, a small mini-ramp, a funbox with rail, and a kicker ramp or two. Reviews note it is "pretty basic, not many ramps" – suitable for casual skating and beginners. It's free and not supervised. Because of its simplicity, local skaters often travel to other parks for more variety. (Note: The name "Sanctuary" is a throwback to a '90s indoor park; this is the county-run facility.)</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (Charlotte County) – free</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> No (fully exposed slab, with only a few nearby trees; bring water and sunscreen)</li>
    <li><strong>Webpage:</strong> <a href="https://www.sanctuaryskatepark.com/">Charlotte County – Skate Parks</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Satellite Beach Skatepark – Satellite Beach, FL</h2>
  <ul>
    <li><strong>Location:</strong> 750 Jamaica Blvd, Satellite Beach, FL 32937</li>
    <li><strong>Distance from Dunedin:</strong> ~130 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2010)</li>
    <li><strong>Features:</strong> 13,500 sq.ft. concrete park featuring a medium bowl, multiple quarter-pipes, bank ramps, stairs, hubba ledges, and rails. The layout is triangular with a central volcano/hip that creates flow between sections. A standout is the vert wall quarter-pipe emblazoned with the city's logo. The park is staffed after school hours (and during summer days); it is free to use but all skaters must have a signed waiver on file. Bikes are allowed only on designated nights. The facility also now includes a newly added pump track (as of 2023) adjacent to the park for bikes and skateboards.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of Satellite Beach) – free (waiver required)</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (Staff on duty Mon–Fri 4–9PM; weekends 4–8PM, with earlier hours in summer)</li>
    <li><strong>Shaded:</strong> Limited – no roof; however, evening sessions are popular (park has lights and cooler temps). Bleachers are shaded.</li>
    <li><strong>Webpage:</strong> <a href="https://www.satellitebeach.org/departments/recreation_department/facilities/satellite_beach_skate_park.php">City of Satellite Beach – Skate/BMX Park</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Skatepark of Tampa (SPoT) – Tampa, FL</h2>
  <ul>
    <li><strong>Location:</strong> 4215 E Columbus Dr, Tampa, FL 33605</li>
    <li><strong>Distance from Dunedin:</strong> ~20 miles</li>
    <li><strong>Builder:</strong> Team Pain & SPoT Crew (est. 1993; updated continuously)</li>
    <li><strong>Features:</strong> World-famous indoor skatepark, home to the annual Tampa Am and Tampa Pro contests. The facility includes indoor wooden street courses that change periodically (featuring stairs, handrails, hubbas, euro gaps, quarter-pipes and banks) and an outdoor concrete vert bowl ("Pro Course" bowl). There is also a concrete outdoor section with additional obstacles. SPoT has a pro shop and skate-centric cafe on site. This park is privately run – helmets required under 18, and session fees or memberships are required. Known for its professional events and as a cradle of skateboarding talent, SPoT is a must-visit for serious skaters.</li>
    <li><strong>Indoor/Outdoor:</strong> Both – majority indoor (wooden courses), plus some outdoor concrete sections</li>
    <li><strong>Public/Private:</strong> Private – admission fee (daily or membership)</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (7 days; hosts events often)</li>
    <li><strong>Shaded:</strong> Yes – indoor areas are fully covered; outdoor bowl is uncovered.</li>
    <li><strong>Webpage:</strong> <a href="https://skateparkoftampa.com/">Skatepark of Tampa – Official Site</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 St. Pete Skatepark (St. Petersburg Regional Skatepark) – St. Petersburg, FL</h2>
  <ul>
    <li><strong>Location:</strong> 601 14th St S, St. Petersburg, FL 33705 (Campbell Park)</li>
    <li><strong>Distance from Dunedin:</strong> ~20 miles</li>
    <li><strong>Builder:</strong> Team Pain Skate Parks (opened 2018)</li>
    <li><strong>Features:</strong> A 28,000 sq.ft. state-of-the-art concrete park, one of the largest in Florida. Beautifully landscaped and integrated into Campbell Park. It offers a massive flowing snake-run/ditch section that winds through the park, leading into multiple bowl areas (including a pro-level bowl ~9' deep and a shallower flow bowl). The street plaza features a multitude of elements: stair sets (3-block, 5-block, etc.), handrails, granite ledges, hubbas, euro gaps, banks, quarter-pipes of varying sizes, and transition gaps. Tall palm trees and grass embankments surround the skate zones, giving a relaxed vibe. The park is free and unsupervised; it has lights until 9 PM. It's often praised as "impossible to find a more beautiful outdoor concrete skatepark".</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (City of St. Petersburg) – free</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span> (dawn to 9 PM)</li>
    <li><strong>Shaded:</strong> Limited – open to sun, but surrounded by large trees and grassy knolls that offer some shade at edges. Some spectator shade structures exist.</li>
    <li><strong>Webpage:</strong> <a href="https://www.stpeteparksrec.org/skatepark.html">City of St. Petersburg – Regional Skatepark</a></li>
  </ul>
</div>

<div class="park-card">
  <h2>🛹 Tarpon Springs Skate Park – Holiday, FL (J. Ben Harrill Rec Complex)</h2>
  <ul>
    <li><strong>Location:</strong> 2830 Gulf Trace Blvd, Holiday, FL 34691 (Pasco County)</li>
    <li><strong>Distance from Dunedin:</strong> ~12 miles</li>
    <li><strong>Builder:</strong> Rampage (prefab modular)</li>
    <li><strong>Features:</strong> A small outdoor skatepark serving North Pinellas/South Pasco. It consists of a fenced asphalt area with modular ramps: quarter pipes, a 4' halfpipe, a funbox with rail, and a wedge ramp. It's a modest setup suitable for beginners and casual sessions. Often referred to locally as the "Holiday Skatepark," it was originally built with involvement from the Ian Tilmann Foundation to promote helmet safety. The recreation complex around it offers restrooms and water fountains.</li>
    <li><strong>Indoor/Outdoor:</strong> Outdoor</li>
    <li><strong>Public/Private:</strong> Public (Pasco County) – free (with county park membership/waiver)</li>
    <li><strong>Status:</strong> <span class="status-open">Open</span></li>
    <li><strong>Shaded:</strong> No (fully exposed, though the complex has some shade trees nearby)</li>
    <li><strong>Webpage:</strong> <a href="https://www.ctsfl.us/recreation/parks/skatepark.htm">Pasco County – J. Ben Harrill Recreation Complex</a></li>
  </ul>
</div>

</div>

<div class="page-footer">
  <p>Last updated: May 2025</p>
  <p><a href="index.html">Return to Home Page</a></p>
</div>
