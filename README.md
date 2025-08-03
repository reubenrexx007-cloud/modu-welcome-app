src/app/layout.tsx (Super simple layout!)
import './globals.css' export default function RootLayout({ children, }: { children: React.ReactNode }) { return ( <html lang="en"> <head> <title>My Simple App</title> <meta name="description" content="A simple Next.js app" /> </head> <body>{children} </body> </html> ) }

🎨 src/app/globals.css (Clean styles!)
@tailwind base; @tailwind components; @tailwind utilities; /* Simple, clean styles */ body { font-family: system-ui, -apple-system, sans-serif; background-color: #f8fafc; color: #1f2937; }
