# ElPrisma — Código completo para replicar

## 📦 Dependencias (package.json)

```json
{
  "dependencies": {
    "react": "^18.3.1",
    "react-dom": "^18.3.1",
    "react-router-dom": "^6.30.1",
    "@tanstack/react-query": "^5.83.0",
    "lucide-react": "^0.462.0",
    "class-variance-authority": "^0.7.1",
    "clsx": "^2.1.1",
    "tailwind-merge": "^2.6.0",
    "tailwindcss-animate": "^1.0.7",
    "sonner": "^1.7.4"
  },
  "devDependencies": {
    "@vitejs/plugin-react-swc": "^3.11.0",
    "autoprefixer": "^10.4.21",
    "postcss": "^8.5.6",
    "tailwindcss": "^3.4.17",
    "typescript": "^5.8.3",
    "vite": "^5.4.19"
  }
}
```

---

## 📁 index.html

```html
<!doctype html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>ElPrisma — Economía con rigor</title>
    <meta name="description" content="ElPrisma: medio de comunicación económico. Dato o Cuento, Que no te líen, Al Grano." />
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.tsx"></script>
  </body>
</html>
```

---

## 📁 src/main.tsx

```tsx
import { createRoot } from "react-dom/client";
import App from "./App.tsx";
import "./index.css";

createRoot(document.getElementById("root")!).render(<App />);
```

---

## 📁 src/App.tsx

```tsx
import { QueryClient, QueryClientProvider } from "@tanstack/react-query";
import { BrowserRouter, Route, Routes } from "react-router-dom";
import { TooltipProvider } from "@/components/ui/tooltip";
import Index from "./pages/Index.tsx";

const queryClient = new QueryClient();

const App = () => (
  <QueryClientProvider client={queryClient}>
    <TooltipProvider>
      <BrowserRouter>
        <Routes>
          <Route path="/" element={<Index />} />
        </Routes>
      </BrowserRouter>
    </TooltipProvider>
  </QueryClientProvider>
);

export default App;
```

---

## 📁 src/index.css (ESTILOS Y DESIGN SYSTEM)

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700;800;900&family=Inter:wght@300;400;500;600;700&display=swap');

@layer base {
  :root {
    --background: 40 20% 97%;
    --foreground: 220 20% 10%;

    --card: 0 0% 100%;
    --card-foreground: 220 20% 10%;

    --popover: 0 0% 100%;
    --popover-foreground: 220 20% 10%;

    --primary: 220 20% 10%;
    --primary-foreground: 40 20% 97%;

    --secondary: 40 15% 92%;
    --secondary-foreground: 220 20% 10%;

    --muted: 40 10% 94%;
    --muted-foreground: 220 10% 46%;

    --accent: 38 92% 50%;
    --accent-foreground: 220 20% 10%;

    --destructive: 0 84% 60%;
    --destructive-foreground: 0 0% 100%;

    --border: 40 15% 88%;
    --input: 40 15% 88%;
    --ring: 38 92% 50%;

    --radius: 0.25rem;

    --nav-height: 56px;
    --section-intro-bg: 220 20% 8%;
    --section-intro-fg: 40 20% 97%;
    --ticker-bg: 220 20% 10%;
    --ticker-fg: 38 92% 50%;
  }
}

@layer base {
  * {
    @apply border-border;
  }
  body {
    @apply bg-background text-foreground antialiased;
    font-family: 'Inter', sans-serif;
  }
  h1, h2, h3, h4, h5 {
    font-family: 'Playfair Display', Georgia, serif;
  }
}

@layer utilities {
  .font-editorial {
    font-family: 'Playfair Display', Georgia, serif;
  }
  .font-sans-ui {
    font-family: 'Inter', sans-serif;
  }
}

/* Animaciones */
@keyframes reveal-up {
  from {
    opacity: 0;
    transform: translateY(16px);
    filter: blur(4px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
    filter: blur(0);
  }
}

@keyframes slide-in-left {
  from {
    opacity: 0;
    transform: translateX(-20px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes ticker-scroll {
  0% { transform: translateX(0); }
  100% { transform: translateX(-50%); }
}

.animate-reveal-up {
  animation: reveal-up 0.6s cubic-bezier(0.16, 1, 0.3, 1) both;
}

.animate-slide-left {
  animation: slide-in-left 0.6s cubic-bezier(0.16, 1, 0.3, 1) both;
}

.animate-ticker {
  animation: ticker-scroll 30s linear infinite;
}

/* Sección intro pantalla completa */
.section-intro {
  background: hsl(var(--section-intro-bg));
  color: hsl(var(--section-intro-fg));
}
```

---

## 📁 tailwind.config.ts

```ts
import type { Config } from "tailwindcss";

export default {
  darkMode: ["class"],
  content: ["./pages/**/*.{ts,tsx}", "./components/**/*.{ts,tsx}", "./app/**/*.{ts,tsx}", "./src/**/*.{ts,tsx}"],
  prefix: "",
  theme: {
    container: {
      center: true,
      padding: "2rem",
      screens: {
        "2xl": "1400px",
      },
    },
    extend: {
      fontFamily: {
        editorial: ['"Playfair Display"', 'Georgia', 'serif'],
        sans: ['Inter', 'sans-serif'],
      },
      colors: {
        border: "hsl(var(--border))",
        input: "hsl(var(--input))",
        ring: "hsl(var(--ring))",
        background: "hsl(var(--background))",
        foreground: "hsl(var(--foreground))",
        primary: {
          DEFAULT: "hsl(var(--primary))",
          foreground: "hsl(var(--primary-foreground))",
        },
        secondary: {
          DEFAULT: "hsl(var(--secondary))",
          foreground: "hsl(var(--secondary-foreground))",
        },
        destructive: {
          DEFAULT: "hsl(var(--destructive))",
          foreground: "hsl(var(--destructive-foreground))",
        },
        muted: {
          DEFAULT: "hsl(var(--muted))",
          foreground: "hsl(var(--muted-foreground))",
        },
        accent: {
          DEFAULT: "hsl(var(--accent))",
          foreground: "hsl(var(--accent-foreground))",
        },
        popover: {
          DEFAULT: "hsl(var(--popover))",
          foreground: "hsl(var(--popover-foreground))",
        },
        card: {
          DEFAULT: "hsl(var(--card))",
          foreground: "hsl(var(--card-foreground))",
        },
      },
      borderRadius: {
        lg: "var(--radius)",
        md: "calc(var(--radius) - 2px)",
        sm: "calc(var(--radius) - 4px)",
      },
      keyframes: {
        "accordion-down": {
          from: { height: "0" },
          to: { height: "var(--radix-accordion-content-height)" },
        },
        "accordion-up": {
          from: { height: "var(--radix-accordion-content-height)" },
          to: { height: "0" },
        },
      },
      animation: {
        "accordion-down": "accordion-down 0.2s ease-out",
        "accordion-up": "accordion-up 0.2s ease-out",
      },
    },
  },
  plugins: [require("tailwindcss-animate")],
} satisfies Config;
```

---

## 📁 src/lib/utils.ts

```ts
import { clsx, type ClassValue } from "clsx";
import { twMerge } from "tailwind-merge";

export function cn(...inputs: ClassValue[]) {
  return twMerge(clsx(inputs));
}
```

---

## 📁 src/pages/Index.tsx (PÁGINA PRINCIPAL)

```tsx
import StickyNav from "@/components/StickyNav";
import NewsGrid from "@/components/NewsGrid";
import AbecedarioSidebar from "@/components/AbecedarioSidebar";
import IbexTicker from "@/components/IbexTicker";
import AskBar from "@/components/AskBar";
import SectionIntro from "@/components/SectionIntro";
import SectionContent from "@/components/SectionContent";

const datoOCuentoArticles = [
  { title: "El paro baja en febrero... pero no todo es lo que parece", category: "¿Dato o Cuento?", summary: "Analizamos las cifras reales detrás del titular optimista del Gobierno.", large: true },
  { title: "¿Realmente España crece más que Alemania?", category: "¿Dato o Cuento?", summary: "Comparamos metodologías estadísticas entre ambos países." },
  { title: "El mito de la deuda pública insostenible", category: "¿Dato o Cuento?", summary: "Qué dicen los números versus la narrativa política." },
  { title: "Salario medio vs salario mediano: la trampa estadística", category: "¿Dato o Cuento?", summary: "Por qué la media salarial no refleja la realidad de la mayoría." },
];

const queNoTeLienArticles = [
  { title: "Cuidado con las ofertas de inversión en redes sociales", category: "Que no te líen", summary: "Detectamos tres esquemas fraudulentos activos en Instagram y TikTok.", large: true },
  { title: "Comisiones ocultas en tu hipoteca", category: "Que no te líen", summary: "Lo que tu banco no te cuenta en la letra pequeña." },
  { title: "Phishing bancario: la nueva ola de 2026", category: "Que no te líen", summary: "Cómo identificar correos falsos de Hacienda y tu banco." },
  { title: "Seguros vinculados: ¿obligatorios o imposición?", category: "Que no te líen", summary: "Lo que dice la ley y lo que hacen las entidades." },
];

const alGranoArticles = [
  { title: "5 claves para entender los presupuestos de 2026", category: "Al Grano", summary: "Todo lo que necesitas saber en 2 minutos de lectura.", large: true },
  { title: "Lo que pasó esta semana en los mercados", category: "Al Grano", summary: "IBEX, Wall Street y materias primas en un vistazo." },
  { title: "Tipos de interés: ¿suben o bajan?", category: "Al Grano", summary: "La decisión del BCE explicada sin jerga." },
  { title: "Renta 2025: lo que debes saber antes de abril", category: "Al Grano", summary: "Deducciones, plazos y novedades fiscales clave." },
];

export default function Index() {
  return (
    <div className="min-h-screen">
      <StickyNav />

      {/* IBEX Ticker fijo abajo */}
      <div className="fixed bottom-0 left-0 right-0 z-40">
        <IbexTicker />
      </div>

      {/* Contenido principal */}
      <main className="pt-14 pb-12">
        {/* === PORTADA === */}
        <section id="portada" className="container py-12">
          <div className="grid grid-cols-1 lg:grid-cols-[1fr_320px] gap-8">
            <div>
              <div className="mb-8">
                <p className="text-xs font-semibold uppercase tracking-[0.25em] text-accent mb-2">Última hora</p>
                <h1 className="font-editorial text-3xl md:text-4xl font-bold leading-tight">
                  Lo que importa, contado con rigor
                </h1>
              </div>
              <NewsGrid />
              <div className="mt-6">
                <AskBar />
              </div>
            </div>

            <div className="space-y-6">
              <AbecedarioSidebar />
            </div>
          </div>
        </section>

        {/* === DATO O CUENTO === */}
        <SectionIntro
          id="dato-o-cuento"
          title="¿Dato o Cuento?"
          description="Separamos los hechos de la ficción. Aquí verificamos los datos que te cuentan y te damos las herramientas para que juzgues por ti mismo."
        />
        <SectionContent articles={datoOCuentoArticles} />

        {/* === QUE NO TE LÍEN === */}
        <SectionIntro
          id="que-no-te-lien"
          title="Que no te líen"
          description="Te protegemos de fraudes, engaños y malas prácticas. Información clara para que tomes mejores decisiones financieras."
        />
        <SectionContent articles={queNoTeLienArticles} />

        {/* === AL GRANO === */}
        <SectionIntro
          id="al-grano"
          title="Al Grano"
          description="Sin rodeos, sin relleno. Las noticias económicas que necesitas saber, resumidas y explicadas de forma directa."
        />
        <SectionContent articles={alGranoArticles} />
      </main>
    </div>
  );
}
```

---

## 📁 src/components/StickyNav.tsx

```tsx
import { useState } from "react";
import { Menu, X } from "lucide-react";

const sections = [
  { id: "portada", label: "Portada" },
  { id: "dato-o-cuento", label: "¿Dato o Cuento?" },
  { id: "que-no-te-lien", label: "Que no te líen" },
  { id: "al-grano", label: "Al Grano" },
];

export default function StickyNav() {
  const [open, setOpen] = useState(false);

  const scrollTo = (id: string) => {
    document.getElementById(id)?.scrollIntoView({ behavior: "smooth" });
    setOpen(false);
  };

  return (
    <nav className="fixed top-0 left-0 right-0 z-50 h-14 bg-primary text-primary-foreground border-b border-primary/80 backdrop-blur-sm">
      <div className="container h-full flex items-center justify-between">
        <button onClick={() => scrollTo("portada")} className="font-editorial text-xl font-bold tracking-tight hover:text-accent transition-colors">
          <span className="text-accent">El</span>Prisma
        </button>

        <ul className="hidden md:flex items-center gap-8">
          {sections.map((s) => (
            <li key={s.id}>
              <button
                onClick={() => scrollTo(s.id)}
                className="font-sans text-sm font-medium uppercase tracking-widest text-primary-foreground/70 hover:text-accent transition-colors"
              >
                {s.label}
              </button>
            </li>
          ))}
        </ul>

        <button className="md:hidden" onClick={() => setOpen(!open)}>
          {open ? <X size={20} /> : <Menu size={20} />}
        </button>
      </div>

      {open && (
        <div className="md:hidden bg-primary border-t border-primary-foreground/10 py-4">
          {sections.map((s) => (
            <button
              key={s.id}
              onClick={() => scrollTo(s.id)}
              className="block w-full text-left px-6 py-3 text-sm uppercase tracking-widest text-primary-foreground/70 hover:text-accent transition-colors"
            >
              {s.label}
            </button>
          ))}
        </div>
      )}
    </nav>
  );
}
```

---

## 📁 src/components/NewsGrid.tsx

```tsx
import { useEffect, useRef } from "react";
import { BookOpen } from "lucide-react";

interface NewsItem {
  title: string;
  category: string;
  summary: string;
  span: string;
  accent?: boolean;
  isBook?: boolean;
}

const news: NewsItem[] = [
  { title: "La inflación se modera al 2,8% en marzo", category: "¿Dato o Cuento?", summary: "El IPC muestra señales de estabilización tras meses de volatilidad en los mercados europeos.", span: "md:col-span-2 md:row-span-2", accent: true },
  { title: "El BCE mantiene los tipos en el 3,5%", category: "Al Grano", summary: "Lagarde señala que las decisiones futuras dependerán de los datos.", span: "md:col-span-1 md:row-span-1" },
  { title: "El hombre que cambió su casa por un tulipán", category: "Libro de la semana", summary: "Fernando Trías de Bes — Un recorrido fascinante por las mayores burbujas financieras de la historia.", span: "md:col-span-1 md:row-span-1", isBook: true },
  { title: "¿Burbuja inmobiliaria o ajuste natural?", category: "¿Dato o Cuento?", summary: "Los precios de la vivienda suben un 6,2% interanual en las grandes capitales.", span: "md:col-span-2 md:row-span-1" },
  { title: "China desacelera: impacto en materias primas", category: "Que no te líen", summary: "El PMI manufacturero cae por tercer mes consecutivo.", span: "md:col-span-1 md:row-span-1" },
  { title: "Las criptomonedas buscan regulación europea", category: "Que no te líen", summary: "MiCA entra en vigor con nuevas obligaciones para emisores.", span: "md:col-span-1 md:row-span-1" },
];

export default function NewsGrid() {
  const ref = useRef<HTMLDivElement>(null);

  useEffect(() => {
    const observer = new IntersectionObserver(
      (entries) => {
        entries.forEach((e) => {
          if (e.isIntersecting) {
            e.target.classList.add("animate-reveal-up");
            observer.unobserve(e.target);
          }
        });
      },
      { threshold: 0.15 }
    );
    ref.current?.querySelectorAll("[data-reveal]").forEach((el) => observer.observe(el));
    return () => observer.disconnect();
  }, []);

  return (
    <div ref={ref} className="grid grid-cols-1 md:grid-cols-3 gap-4">
      {news.map((item, i) => (
        <article
          key={i}
          data-reveal
          style={{ animationDelay: `${i * 80}ms` }}
          className={`${item.span} opacity-0 group cursor-pointer rounded border p-6 flex flex-col justify-end transition-shadow hover:shadow-lg hover:shadow-accent/10 ${item.isBook ? "bg-accent/10 border-accent/20 min-h-[180px]" : "bg-card border-border"} ${item.accent ? "min-h-[340px]" : "min-h-[180px]"}`}
        >
          <span className="text-xs font-sans font-semibold uppercase tracking-widest text-accent mb-2 flex items-center gap-1.5">
            {item.isBook && <BookOpen size={12} />}
            {item.category}
          </span>
          <h3 className={`font-editorial font-bold leading-tight mb-2 group-hover:text-accent transition-colors ${item.accent ? "text-2xl md:text-3xl" : "text-lg"}`}>
            {item.title}
          </h3>
          <p className="text-sm text-muted-foreground leading-relaxed line-clamp-2">
            {item.summary}
          </p>
        </article>
      ))}
    </div>
  );
}
```

---

## 📁 src/components/SectionIntro.tsx

```tsx
import { useEffect, useRef, useState } from "react";

interface SectionIntroProps {
  title: string;
  description: string;
  id: string;
}

export default function SectionIntro({ title, description, id }: SectionIntroProps) {
  const ref = useRef<HTMLDivElement>(null);
  const [visible, setVisible] = useState(false);

  useEffect(() => {
    const observer = new IntersectionObserver(
      ([entry]) => {
        if (entry.isIntersecting) {
          setVisible(true);
          observer.unobserve(entry.target);
        }
      },
      { threshold: 0.3 }
    );
    if (ref.current) observer.observe(ref.current);
    return () => observer.disconnect();
  }, []);

  return (
    <div
      id={id}
      ref={ref}
      className="section-intro min-h-screen flex items-center justify-center px-6 relative overflow-hidden"
    >
      <div className="absolute left-1/2 top-0 w-px h-full bg-accent/20" />

      <div
        className={`text-center max-w-2xl transition-all duration-700 ${
          visible ? "opacity-100 translate-y-0" : "opacity-0 translate-y-8"
        }`}
        style={{ transitionTimingFunction: "cubic-bezier(0.16, 1, 0.3, 1)" }}
      >
        <span className="inline-block text-accent text-xs font-semibold uppercase tracking-[0.3em] mb-6">
          Sección
        </span>
        <h2 className="font-editorial text-4xl md:text-6xl font-bold mb-6 leading-[1.1]">
          {title}
        </h2>
        <p className="text-lg text-primary-foreground/60 leading-relaxed max-w-lg mx-auto">
          {description}
        </p>
        <div className="mt-8 w-16 h-0.5 bg-accent mx-auto" />
      </div>
    </div>
  );
}
```

---

## 📁 src/components/SectionContent.tsx

```tsx
import { useEffect, useRef } from "react";

interface Article {
  title: string;
  category: string;
  summary: string;
  large?: boolean;
}

interface SectionContentProps {
  articles: Article[];
}

export default function SectionContent({ articles }: SectionContentProps) {
  const ref = useRef<HTMLDivElement>(null);

  useEffect(() => {
    const observer = new IntersectionObserver(
      (entries) => {
        entries.forEach((e) => {
          if (e.isIntersecting) {
            e.target.classList.add("animate-reveal-up");
            observer.unobserve(e.target);
          }
        });
      },
      { threshold: 0.15 }
    );
    ref.current?.querySelectorAll("[data-reveal]").forEach((el) => observer.observe(el));
    return () => observer.disconnect();
  }, []);

  return (
    <div ref={ref} className="container py-16">
      <div className="grid grid-cols-1 md:grid-cols-3 gap-4">
        {articles.map((a, i) => (
          <article
            key={i}
            data-reveal
            style={{ animationDelay: `${i * 80}ms` }}
            className={`opacity-0 group cursor-pointer rounded bg-card border border-border p-6 flex flex-col justify-end transition-shadow hover:shadow-lg hover:shadow-accent/10 ${
              a.large ? "md:col-span-2 md:row-span-2 min-h-[300px]" : "min-h-[180px]"
            }`}
          >
            <span className="text-xs font-sans font-semibold uppercase tracking-widest text-accent mb-2">
              {a.category}
            </span>
            <h3 className={`font-editorial font-bold leading-tight mb-2 group-hover:text-accent transition-colors ${a.large ? "text-2xl" : "text-lg"}`}>
              {a.title}
            </h3>
            <p className="text-sm text-muted-foreground leading-relaxed line-clamp-2">
              {a.summary}
            </p>
          </article>
        ))}
      </div>
    </div>
  );
}
```

---

## 📁 src/components/AbecedarioSidebar.tsx

```tsx
const terms = [
  { letter: "A", term: "Amortización", def: "Pago gradual de una deuda." },
  { letter: "B", term: "Bonos", def: "Títulos de deuda emitidos por gobiernos o empresas." },
  { letter: "C", term: "Capitalización", def: "Valor total de mercado de una empresa." },
  { letter: "D", term: "Dividendo", def: "Beneficio repartido a los accionistas." },
  { letter: "E", term: "EBITDA", def: "Beneficio antes de intereses, impuestos y amortizaciones." },
  { letter: "F", term: "Fondo indexado", def: "Fondo que replica un índice bursátil." },
  { letter: "G", term: "Gasto público", def: "Inversión del Estado en servicios y bienes." },
];

export default function AbecedarioSidebar() {
  return (
    <aside className="bg-card border border-border rounded p-5 sticky top-20">
      <h3 className="font-editorial text-lg font-bold mb-4 pb-3 border-b border-border">
        Abecedario <span className="text-accent">Económico</span>
      </h3>
      <ul className="space-y-4">
        {terms.map((t) => (
          <li key={t.letter} className="group">
            <div className="flex items-start gap-3">
              <span className="flex-shrink-0 w-8 h-8 rounded bg-accent/10 text-accent font-editorial font-bold text-sm flex items-center justify-center">
                {t.letter}
              </span>
              <div>
                <p className="text-sm font-semibold group-hover:text-accent transition-colors">{t.term}</p>
                <p className="text-xs text-muted-foreground leading-relaxed">{t.def}</p>
              </div>
            </div>
          </li>
        ))}
      </ul>
    </aside>
  );
}
```

---

## 📁 src/components/IbexTicker.tsx

```tsx
import { TrendingUp, TrendingDown } from "lucide-react";

const stocks = [
  { name: "IBEX 35", value: "11.247,30", change: "+0.82%", up: true },
  { name: "Inditex", value: "38,92", change: "+1.14%", up: true },
  { name: "Santander", value: "4,87", change: "-0.41%", up: false },
  { name: "Telefónica", value: "4,12", change: "+0.24%", up: true },
  { name: "BBVA", value: "9,63", change: "+0.93%", up: true },
  { name: "Repsol", value: "13,45", change: "-1.02%", up: false },
  { name: "Iberdrola", value: "12,78", change: "+0.67%", up: true },
  { name: "CaixaBank", value: "5,34", change: "+0.38%", up: true },
  { name: "Amadeus", value: "63,20", change: "-0.15%", up: false },
  { name: "Ferrovial", value: "37,85", change: "+1.56%", up: true },
];

export default function IbexTicker() {
  const doubled = [...stocks, ...stocks];

  return (
    <div className="w-full overflow-hidden bg-primary py-3">
      <div className="animate-ticker flex whitespace-nowrap">
        {doubled.map((s, i) => (
          <div key={i} className="inline-flex items-center gap-2 mx-6">
            <span className="text-primary-foreground/60 text-xs font-semibold uppercase tracking-wide">{s.name}</span>
            <span className="text-primary-foreground text-sm font-medium">{s.value}</span>
            <span className={`text-xs font-semibold flex items-center gap-0.5 ${s.up ? "text-emerald-400" : "text-red-400"}`}>
              {s.up ? <TrendingUp size={12} /> : <TrendingDown size={12} />}
              {s.change}
            </span>
          </div>
        ))}
      </div>
    </div>
  );
}
```

---

## 📁 src/components/AskBar.tsx

```tsx
import { useState } from "react";
import { Send } from "lucide-react";

export default function AskBar() {
  const [question, setQuestion] = useState("");
  const [submitted, setSubmitted] = useState(false);

  const handleSubmit = (e: React.FormEvent) => {
    e.preventDefault();
    if (!question.trim()) return;
    setSubmitted(true);
    setQuestion("");
    setTimeout(() => setSubmitted(false), 3000);
  };

  return (
    <div className="bg-card border border-border rounded p-6">
      <h3 className="font-editorial text-lg font-bold mb-1">
        Pregúntalo <span className="text-accent">sin miedo</span>
      </h3>
      <p className="text-xs text-muted-foreground mb-4">
        Envía tu pregunta sobre economía, finanzas o actualidad. La responderemos en el próximo programa.
      </p>

      {submitted ? (
        <div className="bg-accent/10 text-accent text-sm font-medium rounded px-4 py-3 text-center">
          ¡Gracias! Tu pregunta ha sido enviada. 🎙️
        </div>
      ) : (
        <form onSubmit={handleSubmit} className="flex gap-2">
          <input
            type="text"
            value={question}
            onChange={(e) => setQuestion(e.target.value)}
            placeholder="¿Qué quieres saber?"
            className="flex-1 bg-secondary border-none rounded px-4 py-2.5 text-sm placeholder:text-muted-foreground focus:outline-none focus:ring-2 focus:ring-accent"
          />
          <button
            type="submit"
            className="bg-accent text-accent-foreground rounded px-4 py-2.5 font-medium text-sm hover:bg-accent/90 transition-colors active:scale-95"
          >
            <Send size={16} />
          </button>
        </form>
      )}
    </div>
  );
}
```

---

## 📁 vite.config.ts

```ts
import { defineConfig } from "vite";
import react from "@vitejs/plugin-react-swc";
import path from "path";

export default defineConfig({
  server: {
    host: "::",
    port: 8080,
  },
  plugins: [react()],
  resolve: {
    alias: {
      "@": path.resolve(__dirname, "./src"),
    },
  },
});
```

---

## 📁 postcss.config.js

```js
export default {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
};
```

---

## 📁 tsconfig.json

```json
{
  "compilerOptions": {
    "target": "ES2020",
    "useDefineForClassFields": true,
    "lib": ["ES2020", "DOM", "DOM.Iterable"],
    "module": "ESNext",
    "skipLibCheck": true,
    "moduleResolution": "bundler",
    "allowImportingTsExtensions": true,
    "resolveJsonModule": true,
    "isolatedModules": true,
    "noEmit": true,
    "jsx": "react-jsx",
    "strict": true,
    "noUnusedLocals": false,
    "noUnusedParameters": false,
    "noFallthroughCasesInSwitch": true,
    "baseUrl": ".",
    "paths": {
      "@/*": ["./src/*"]
    }
  },
  "include": ["src"]
}
```

---

## 🚀 INSTRUCCIONES DE INSTALACIÓN

```bash
# 1. Crear proyecto
npm create vite@latest elprisma -- --template react-ts

# 2. Instalar dependencias
cd elprisma
npm install react-router-dom @tanstack/react-query lucide-react class-variance-authority clsx tailwind-merge tailwindcss-animate sonner

# 3. Instalar dev dependencies
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

# 4. Copiar todos los archivos de arriba en sus rutas correspondientes

# 5. Arrancar
npm run dev
```
