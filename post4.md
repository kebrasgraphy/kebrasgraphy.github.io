# OSINT EXERCISE #003

This is the writeup of my process for OSINT Exercise #003 by [Sofia Santos](gralhix.com). The challenge was accompanied by the following image:

![The original image, a screenshot of a news article with a photo of the presidents of Somalia and Turkey.](/docs/assets/osint003/osintexercise003.webp)

And the following task briefing:

> In April 2017 Mohamed Abdullahi Farmaajo, the then president of Somalia, visited Turkey. A news agency published a photo where he was seen shaking hands with Recep Tayyip Erdoğan, the country’s president. The article did not disclose where the photo was taken. Your task is to find out the name and coordinates of the location seen below.

I began by searching various combinations of the given names, the month and year, and situation descriptions such as “visit to Turkey”. Through various searches, I found some potential names and locations to search, as my first guess is that this is a significant government building. One such location is Turkey’s parliament building, the Grand National Assembly. However, on an image search of the building, it does not appear to match.

Incidentally, looking through news articles, I found an article about a different visit to Turkey, by the Rwandan president, with a photo of the same building in the original image. Here, it’s named: Ankara’s Presidential Complex.

![A screenshot of a different news article, but with a photo in front of the same doorway.](/docs/assets/osint003/newsarticle.png)

This photo of the doorways matches that in the original image.

![A clear photo of the doorway details, which match the original image.](/docs/assets/osint003/complexdoors.png)

There are a couple of things we must figure out from here. 

![An overhead shot of the Presidential Complex.](/docs/assets/osint003/complexoverhead.png)

There's no street view of this area in Google Earth, and, based on photos, the complex appears to have doors on at least two sides. An image search has yielded an entry on [Wikimapia](https://wikimapia.org/25783996/Presidential-Palace-of-the-Republic-of-Turkey), and several photos of the building from different angles. The doors on the front and the back of the building both have those three center circular features; however, we can look at the surrounding features of the doorway and overhanging roof to rule things out. Between these photos, and photos uploaded to Google Maps, we can orient ourselves.

![The front courtyard of the Presidential Complex, with wide and empty space.](/docs/assets/osint003/complexfront.png)
![The back courtyard of the Presidential Complex, with a pond and additional landscaping.](/docs/assets/osint003/complexback.png)

The doors on the southwest side, which opens into a wide courtyard with a water feature and other landscaping, lacks some of the details that are present in the photo. There is no overhang, and is missing some of the features that outline the doorways, such as the pillars and golden inset panels. Various photos of the northwest side of the building, the front facing the street, seems to match much better. This places the correct doorways in front of a larger, otherwise empty, concrete thoroughfare. 

![An overhead shot of the Presidiental Complex, with a marker at the front of the building approximately where the original photo was taken.](/docs/assets/osint003/finallocation.png)

In conclusion, the answers to the original requirements:

1) The name of the building is the **Presidential Complex** in Ankara
2) The coordinates of the original photo are approximately:  **39°55'52.21"N,  32°47'58.62"E**
