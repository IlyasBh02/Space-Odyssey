Space Odyssey
==============

A simple, static website that presents space exploration content: planets, famous missions, and project information. Built with HTML/CSS.

Structure
---------
- `index.html`: Landing page
- `planets.html`: Planets overview
- `missions.html`: Space missions (grid of 10+ missions with images, agencies, dates, objectives)
- `about.html`: About the project
- `contact.html`: Contact form/info
- `css/`: Stylesheet(s)
- `img/`: Images and icons

How to run locally
------------------
Open `index.html` directly in your browser, or serve the folder with a lightweight server:

Windows PowerShell
```
powershell -c "Start-Process msedge index.html"
```

Python (any OS)
```
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

Accessibility and i18n
----------------------
- Semantic sections and ARIA labels where relevant (e.g., nav, hero).
- Text content primarily in French (fr), with language control in the navbar UI.

Credits
-------
- Images: NASA/ESA/CSA/Wikipedia media (attribution varies by file). External images are hot-linked for mission cards; replace with local assets if needed.
- Fonts: Google Fonts (Poppins, Roboto, Poltawski Nowy).

License
-------
This project is provided as-is for educational/demo purposes.
