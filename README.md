# emojiördinates

Because [What3Words](http://what3words.com/) is stupid, here's a thing that converts a lat/long into 4 emoji, and back. It doesn't do anything clever with projections or tilings - it just scales lat and longs linearly onto a 2×(766²)×(766²) grid, and maps that onto four emoji, picked from the set of 912 that emojiOne can render without any combining characters.

The encoding is completely dependent on the set of emoji I chose, and their order - I think they're in ascending Unicode order.
