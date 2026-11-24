# Festival Prize Finder

A single page for browsing films that won top prizes at eight film festivals, and for letting it pick one for you.

Prizes covered: Palme d'Or, Grand Prix, Prix Un Certain Regard and Caméra d'Or (Cannes); Golden Lion and Grand Jury Prize (Venice); Golden Bear and Silver Bear Grand Jury Prize (Berlin); Grand Jury Prize, U.S. Dramatic and World Cinema Dramatic (Sundance); Golden Leopard (Locarno); Tiger Award (Rotterdam); Crystal Globe (Karlovy Vary); Golden Shell (San Sebastián).

## Using it

Open the page, narrow the list by prize level, festival, years, country or search, then press "Pick a film for me". Each film links to Letterboxd, IMDb, MUBI and JustWatch Portugal. "Watchlist", "Seen" and "Not for me" are saved in the browser of whoever uses the page.

## Data

`films.json` was built from the English Wikipedia winner lists in November 2026, with editions the lists had not yet added (Sundance 2024 to 2026, Tiger Award 2025 and 2026, Golden Shell 2026) checked against festival and trade sources. Fields: `t` title, `o` original title, `d` director, `c` countries, `y` year, `w` Wikipedia article path, `a` prizes as `[festival, prize, level, year]`.
