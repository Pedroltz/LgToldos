# LG Toldos - Institutional Website

A clean and responsive institutional website for **LG Toldos & Estruturas Metalicas LTDA**, a company specializing in awnings, metal structures, roofing, and related services based in Barra Bonita, Sao Paulo, Brazil.

## About

This is a single-page showcase website built to present the company's services, differentials, and contact information. The design is mobile-first, focusing on simplicity and usability across all devices.

## Tech Stack

- ASP.NET Core 9.0 (Razor Pages)
- Bootstrap 5
- Bootstrap Icons
- Google Fonts (Inter)
- Vanilla JavaScript

## Features

- Fully responsive layout with mobile-first approach
- Fixed navbar with scroll-based style transition
- Smooth scroll navigation between sections
- Fade-in animations on scroll (Intersection Observer)
- Floating WhatsApp button for quick contact
- Embedded Google Maps location
- SEO meta tags and Open Graph support

## Sections

- **Hero** - Main banner with call-to-action buttons and key stats
- **About** - Company overview and core values
- **Services** - Awnings, pergolas, retractable curtains, roofing, handrails, stairs, gutters
- **Coverage Types** - Detailed breakdown of roofing options
- **Differentials** - Quality indicators and company strengths
- **Contact** - WhatsApp, email, Instagram, and map

## Getting Started

### Prerequisites

- .NET 9.0 SDK

### Run

```bash
cd LgToldos
dotnet run
```

The application will start at `http://localhost:5000` by default.

### Build

```bash
dotnet build
```

### Publish

```bash
dotnet publish -c Release
```

## Project Structure

```
LgToldos/
  Pages/
    Index.cshtml            # Main page with all sections
    Shared/
      _Layout.cshtml        # Layout with navbar and footer
  wwwroot/
    css/
      site.css              # Custom styles
    js/
      site.js               # Navbar, scroll, and animation logic
    imgs/                   # Images and logos
```

## License

All rights reserved. This project was built exclusively for LG Toldos & Estruturas Metalicas LTDA.
