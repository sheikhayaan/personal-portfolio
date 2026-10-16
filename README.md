# Personal Portfolio

My personal site — **[personal-portfolio-compiq.vercel.app](https://personal-portfolio-compiq.vercel.app)**

A single-page portfolio covering my open source work, experience, and projects. Built as a self-contained `index.html` with no build step, so it deploys anywhere instantly.

## What's in it

- **Hero** — role, focus areas, and quick links (resume, GitHub, LinkedIn, LeetCode)
- **Interactive 3D / WebGL background** with a scroll-reveal system
- **Open source** section — merged contributions to ArviZ and Zarr, linked to the actual PRs
- **Experience** — ITJOBXS (SDE Intern), C-DAC Noida (Cybersecurity), Smart India Hackathon 2025
  - Includes interactive flow diagrams rendered as SVG (internship pipeline, vulnerability audit path, hackathon team topology)
- **Projects**, **Skills**, **Achievements**, **Contact**
- Fully responsive, no framework, no dependencies to install

## Stack

`HTML` `CSS` `JavaScript` `WebGL` `SVG` `Vercel`

## Running locally

No build step and no dependencies:

```bash
git clone https://github.com/sheikhayaan/personal-portfolio.git
cd personal-portfolio
```

Then just open `index.html` in a browser. Or serve it:

```bash
python -m http.server 8000
# open http://localhost:8000
```

## Deploying

Connected to Vercel. Every push to `main` redeploys automatically. Any static host works — the site is a single HTML file plus a logo asset.

---

**Contact** — [sheikhayaan408@gmail.com](mailto:sheikhayaan408@gmail.com) · [LinkedIn](https://linkedin.com/in/mohd-ayaan-7731b4381)
