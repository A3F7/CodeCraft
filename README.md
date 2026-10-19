# CodeCraft — C++ Lab

Static single-file site (no build step). All CSS, JS, fonts and images are embedded in `index.html`.

## CodeCraft Lab
The `#/lab` page compiles real C++ (GCC) through public online compilers (Wandbox, then Compiler Explorer). If both are unreachable it falls back to the built-in mini interpreter.

## Deploy on Vercel
**Option A — Dashboard:** push this folder to GitHub → Vercel → Add New Project → import repo → Framework Preset: **Other** → Deploy (leave Build Command and Output Directory empty).

**Option B — CLI:**
```
npm i -g vercel
vercel        # preview
vercel --prod # production
```
