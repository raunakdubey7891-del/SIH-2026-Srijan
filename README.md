# Srijan: AI-Driven Market Linkage and Smart Cataloging App for Marginalized Artisans

**Internal Smart India Hackathon 2026, Pondicherry University**
Department of Computer Science, School of Engineering and Technology (17.09.2026)

| | |
|---|---|
| **Problem Statement ID** | SIH26090 |
| **Theme** | Heritage & Culture |
| **Category** | Software |
| **Team** | Srijan (Team ID: P49) |

## The Problem

Marginalized artisans depend on seasonal fairs for their income. A lack of year-round online selling and limited digital skills restrict their customers, market reach and earnings.

## Our Idea

An AI-powered mobile app that turns an artisan's phone camera into an online shop. With one photo and a few spoken words, the AI improves the image, writes the product listing, suggests a price, and helps sell products throughout the year.

## Key Features

- **AI Image Studio:** removes background clutter, improves lighting and enhances product photos for online selling.
- **Multilingual Auto-Cataloger:** artisans describe products by voice in regional languages, and AI creates Hindi and English product descriptions that keep the artisan's own story.
- **Dynamic Pricing Assistant:** suggests a selling price using raw material costs, product details and current market trends.
- **Digital Storefront & Sales Analytics:** a year-round online marketplace with a simple dashboard for orders, earnings and demand trends.
- **Voice-first, low-literacy-friendly design:** complex tasks are hidden behind a simple interface so artisans can focus on their craft.

## Challenges and How We Address Them

| Challenge | Our approach |
|---|---|
| Data security and privacy (unauthorized access, third-party APIs) | Encrypted API connections, strong user authentication |
| Limited digital awareness | Simple navigation, regional language support |
| High traffic in peak seasons, slow AI processing | Cloud auto-scaling, optimized image processing |

## Expected Impact

- **Social:** dignity and a connected community for artisans, and preservation of traditional crafts.
- **Economic:** year-round income, and higher earnings by cutting out middlemen.
- **Environmental:** less travel to physical fairs, and promotion of low-impact, natural-material crafts.
- **Learning:** builds digital and financial literacy through repeated, guided use.
- **Technological:** introduces AI tools to first-time digital users.

## Presentation

📄 [View the presentation (PDF)](./SIH-2026-Srijan.pdf)

## Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | Flutter / Dart |
| **Backend** | Node.js, Express.js |
| **Database** | PostgreSQL / Supabase |
| **AI & ML** | Python, OpenAI Whisper, OpenCV, LLMs |
| **Image Processing** | Cloudinary (image enhancement, background removal, new background per product category) |
| **Content Generation** | ChatGPT / DeepSeek (product title, description, catchy words and tags) |
| **API Services** | REST API |
| **Deployment & Tools** | AWS / Render, Docker, GitHub, Git |

### Product Listing Workflow

1. **Input:** the artisan uploads a product photo and describes the product by voice.
2. **Image processing:** Cloudinary enhances the image, removes the background and sets a new one.
3. **Speech to text:** Whisper converts the seller's voice into text.
4. **Content generation:** an LLM creates the title, description and catchy tags.
5. **Data repository:** the processed image and generated content are stored.
6. **Listing creation:** image, title, description and tags are combined into a catalogue listing.
7. **Marketplace integration:** the listing is published to online marketplaces and goes live.

## Team Srijan

- Raunak Dubey
- Sahil Kumar Singh
- Yash Pathak
- Vikram Kumar Modi
- Prem Kumar Devangan
- Muskan Rathore

## References

- https://socialjustice.gov.in/schemes/13
- https://socialjustice.gov.in/schemes/100
- https://socialjustice.gov.in/schemes/104
- https://socialjustice.gov.in/schemes/99
- https://socialjustice.gov.in/schemes/32
