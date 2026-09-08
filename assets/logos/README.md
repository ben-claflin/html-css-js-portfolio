# Logos

The landing page (`/index.html`) looks for these five files. Drop the image
files in here with exactly these names:

| File               | Organization                                                        |
| ------------------ | ------------------------------------------------------------------- |
| `cdao.png`         | CDAO (Chief Digital and Artificial Intelligence Office)             |
| `inr.png`          | U.S. Department of State, Bureau of Intelligence and Research (INR) |
| `marlinspike.png`  | Marlinspike                                                          |
| `shi.png`          | SHI                                                                  |
| `ut-austin.png`    | The University of Texas at Austin                                    |

Transparent PNG (or SVG, if you also update the `src` in `index.html`) at
roughly 300px on the long edge works well — the page scales each logo to a
68px-tall row.

Until a file is present, the page shows the organization's name as text in
its place, so nothing renders as a broken image.
