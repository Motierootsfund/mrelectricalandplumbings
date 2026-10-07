# MR Electrical & Plumbing Solutions Website

A bright, professional, responsive one-page company website built with plain HTML, CSS and JavaScript. It is ready for GitHub + Vercel and needs no build step.

## Project structure

```text
mr-electrical-plumbing-site/
├── index.html
├── README.md
└── images/
    ├── logo.webp
    ├── lighting-installation.webp
    ├── distribution-board.webp
    ├── power-socket.webp
    ├── wall-switch.webp
    ├── copper-plumbing-valve.webp
    ├── bathroom-sink.webp
    ├── toilet-installation.webp
    ├── drainage-pipes.webp
    ├── water-tank.webp
    ├── water-meter.webp
    ├── cctv-camera.webp
    └── access-control.webp
```

## What is included
- Bright light UI with the company red/blue identity.
- Responsive mobile, tablet and desktop navigation.
- Company information, team, services, process, why-choose-us and contact sections.
- A real-project gallery using all supplied company photographs.
- Gallery filtering for Electrical, Plumbing and Security work.
- Tap/click photo viewer for larger images.
- Direct call, WhatsApp and email actions.
- Quote form that prepares the request in WhatsApp or the visitor's email app.
- SEO title/description and accessibility-friendly labels.
- No external frameworks and no build command required.

## Important: the photos ARE part of the website
The photographs are stored as separate optimized `.webp` files inside the `images/` folder. They are not embedded into `index.html`, so the HTML stays lightweight while the website still displays the real company photos.

GitHub can store these image files normally. Each image in this package is well below GitHub's browser-upload file-size limit, and the complete site is small enough for a normal repository.

## GitHub upload
1. Create a new GitHub repository.
2. Upload `index.html`.
3. Create an `images` folder in the repository and upload everything from this package's `images/` folder into it.
4. Commit the changes.

The final repository should look like the project structure shown above.

## Vercel deployment
1. Sign in to Vercel.
2. Choose **Add New Project** and import the GitHub repository.
3. For this static site, leave the build command empty and deploy.
4. Vercel will serve `index.html` from the repository root.

## Company details used
- Established: 2022
- Registered: January 2026
- CIPC registration number: 2026/083265/07
- SARS Registered
- B-BBEE Compliant
- Service areas: Pretoria, Johannesburg and surrounding areas
- Email: Mrelectricalandplumbing@outlook.com
- Phone: 081-214-0657 / 071-637-2553
- Services: electrical, plumbing, solar geyser installations, security & CCTV

## Contact behavior
- Phone buttons open the phone dialer.
- WhatsApp buttons open a pre-filled WhatsApp message to 081-214-0657.
- The quote form can open WhatsApp or the visitor's default email app.
- No server-side database or form service is required.


## Company profile
The website includes `MR-Electrical-Plumbing-Company-Profile.pdf` in the same root folder as `index.html`. The **View Company Profile** buttons open the profile in a new browser tab on Vercel.
