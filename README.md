## 🚀 Quick Start

### Prerequisites

- Node.js 18+ and npm/yarn/pnpm
- Git

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd my-project
```

2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📁 Project Structure

```

```

## 🎨 Design System

### Typography

- **Body Font**: 
- **Headings**: 

### Colors

- **Background**: 
- **Text**: 
- **Gradients**:
  - Primary: 
  - Secondary: 

### Spacing

- **Section spacing**: 
- **Component spacing**: 

### Buttons

- **Height**: 4
- **Border radius**: 1
- **Primary**: 
- **Secondary**: 

## 🖼️ Image Assets

### Required Images

Place the following images in `../assets/images/`:
1. 

### Image Optimization

- Export images in 3 sizes: 400px, 800px, 1600px
- Provide WebP versions for each
- Use Next.js Image component with `srcset` for responsive loading
- Include blurred LQIP (Low Quality Image Placeholder) for hero and founder images

### Current Image Usage

The site currently uses images from `xyz` directory. You can replace these with optimized versions in `abc` as needed.

## 📄 PDF Assets

Place the company profile PDF at:

- `/public/downloads/xyz.pdf`

## 🚢 Deployment

### Vercel (Recommended)

1. Push your code to GitHub/GitLab/Bitbucket
2. Import the project in [Vercel](https://vercel.com)
3. Vercel will automatically detect Next.js and configure build settings
4. Deploy!

### Manual Build

```bash
npm run build
npm start
```

### Environment Variables

For production, configure:

- Contact form submission endpoint (if using custom API)
- Analytics IDs (if needed)
- Social media links (if available)

## ✅ QA Checklist

### Performance

- [ ] Lighthouse score > 90 for Performance, Accessibility, Best Practices, SEO
- [ ] Images optimized (WebP format, proper sizing)
- [ ] Lazy loading enabled for non-critical images
- [ ] Fonts loaded with `display: swap`

### Accessibility

- [ ] WCAG AA compliance
- [ ] All images have descriptive alt text
- [ ] Form inputs have proper labels and ARIA attributes
- [ ] Keyboard navigation works throughout
- [ ] Color contrast meets WCAG standards
- [ ] `prefers-reduced-motion` respected

### SEO

- [ ] All pages have unique titles and meta descriptions
- [ ] OpenGraph tags configured
- [ ] Twitter Card metadata added
- [ ] Structured data (Schema.org) implemented
- [ ] Sitemap.xml generated (if needed)
- [ ] robots.txt configured (if needed)

### Functionality

- [ ] All links work correctly
- [ ] Contact form submits successfully
- [ ] PDF download works
- [ ] Mobile navigation functions properly
- [ ] Responsive design tested on multiple devices
- [ ] Cross-browser compatibility (Chrome, Firefox, Safari, Edge)

## 🔧 Customization

### Updating Contact Information

Edit contact details in:

- `components/Footer.tsx`
- `components/Header.tsx`

### Modifying Content

- Home page: `app/page.tsx`
- About page: `app/about/page.tsx`
- Contact: `app/contact/page.tsx`

### Styling

- Global styles: `app/globals.css`
- Component styles: Tailwind classes in component files
- Design tokens: CSS variables in `globals.css`

## 📧 Contact Form Setup

The contact form currently uses a placeholder submission handler. For production:

1. **Option 1: Formspree/Netlify Forms**

   - Sign up for Formspree or use Netlify Forms
   - 

2. **Option 2: Custom API Route**

   - 

3. **Option 3: Serverless Function**
   - Deploy serverless function (Vercel, AWS Lambda, etc.)
   - Update form endpoint

## 🛠️ Tech Stack

- **Framework**: Next.js 16 (App Router)
- **React**: 19.2.0
- **Styling**: Tailwind CSS 4
- **TypeScript**: 5.x
- **Icons**: Lucide React
- **Fonts**: Inter, Playfair Display (Google Fonts)

## 📝 License


## 👥 Support

For technical support or questions about the website, contact the development team.

---
