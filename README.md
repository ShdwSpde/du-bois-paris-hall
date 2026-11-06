# Du Bois Does Data: the Paris 1900 Hall

A walk-through model of the hall at the 1900 Paris Exposition where W.E.B. Du Bois and his Atlanta University students showed their hand-drawn charts of Black life in America.

![Walking the Paris 1900 Hall](assets/paris-hall.gif)

Try it at [vr-cave-gallery.vercel.app/#hall](https://vr-cave-gallery.vercel.app/#hall) on a computer, a phone or a Meta Quest headset. There's also a [30-second demo video](https://radicalimagination.xyz/demos/paris-hall.mp4), silent with captions.

## What's in it

- 69 of the exhibit's charts. Each one carries its title, read off the chart itself, and a link to its Library of Congress record (LOT 11931).
- Each chart names its series: the Georgia series by Du Bois or the national series by his students. The title panel credits Du Bois, his students, Thomas J. Calloway and Daniel Murray, and names the colonial displays that were also at the fair.
- Period recordings play in the hall, including the Dinwiddie Colored Quartet (Victor, 1902), which is public domain and comes from the Library of Congress National Jukebox.

## How it's built

React Three Fiber and WebXR on Vite, hosted on Vercel. The chart titles and links are generated from the Library of Congress catalog. Before release, a cultural review checked each caption against its source.

## Related

- [dubois-does-data-notebooks](https://github.com/ShdwSpde/dubois-does-data-notebooks): Colab notebooks that rebuild the charts with current data.
- [dubois-does-data-lessons](https://github.com/ShdwSpde/dubois-does-data-lessons): the classroom lessons.
- The hall was shown with CUNY's Public Interest Technology Lab at the Oculus for Juneteenth, June 2026.

The app's code is in a private repository; this repo is the public page for it.

Made by [Radical Imagination](https://radicalimagination.xyz), a cultural technology studio in Queens.
