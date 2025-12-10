<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Integrated Safety & Leadership Solutions | People. Preparedness. Protection.</title>
  <meta name="description" content="AHA CPR/AED training, EHS consulting, HR risk management, and leadership development in Indianapolis. Bridging compliance and culture to build resilient organizations." />

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Brand theme -->
  <style>
    :root {
      --brand-green: #2f7b4f;
      --brand-green-soft: #3f8f60;
      --brand-yellow: #e6b64a;
      --brand-red: #c9473c;
      --brand-cream: #faf5ef;
      --text-main: #0f172a;
    }

    .btn-primary {
      background: var(--brand-green-soft);
      color: #ffffff;
      border-radius: 9999px;
      padding: 0.75rem 1.5rem;
      font-weight: 600;
      font-size: 0.95rem;
      box-shadow: 0 12px 30px rgba(15, 118, 110, 0.25);
      transition: transform 0.15s ease, box-shadow 0.15s ease, background 0.15s ease;
    }
    .btn-primary:hover {
      background: var(--brand-green);
      transform: translateY(-1px);
      box-shadow: 0 16px 40px rgba(15, 118, 110, 0.35);
    }

    .btn-ghost {
      border-radius: 9999px;
      padding: 0.75rem 1.5rem;
      font-weight: 500;
      font-size: 0.95rem;
      border: 1px solid rgba(148, 163, 184, 0.7);
      color: #0f172a;
      background: #ffffff;
      transition: background 0.15s ease, border-color 0.15s ease;
    }
    .btn-ghost:hover {
      background: #f8fafc;
      border-color: var(--brand-green-soft);
    }

    .hero-bg {
      background: radial-gradient(circle at top left, rgba(46, 139, 87, 0.18), transparent 55%),
                  radial-gradient(circle at top right, rgba(201, 71, 60, 0.18), transparent 55%),
                  linear-gradient(to bottom, #ffffff, #f9fafb);
    }

    .section-label {
      letter-spacing: 0.16em;
      text-transform: uppercase;
      font-size: 0.7rem;
      font-weight: 600;
      color: #6b7280;
    }

    .card-soft {
      border-radius: 1.25rem;
      border: 1px solid rgba(148, 163, 184, 0.4);
      background: #ffffff;
      box-shadow: 0 18px 60px rgba(15, 23, 42, 0.06);
    }

    .pill {
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      border-radius: 9999px;
      padding: 0.25rem 0.75rem;
      font-size: 0.7rem;
      font-weight: 500;
      background: rgba(15, 118, 110, 0.06);
      color: #0f172a;
    }

    .pill-dot {
      display: inline-block;
      width: 0.6rem;
      height: 0.6rem;
      border-radius: 999px;
      background: var(--brand-green-soft);
    }
  </style>

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "ProfessionalService",
    "name": "Integrated Safety & Leadership Solutions",
    "alternateName": "People. Preparedness. Protection.",
    "url": "https://example.com",
    "description": "AHA CPR/AED training, EHS consulting, HR risk mitigation, and leadership development in Indianapolis.",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Indianapolis",
      "addressRegion": "IN",
      "addressCountry": "US"
    },
    "telephone": "+1-832-343-9970"
  }
  </script>
</head>
<body class="bg-white text-slate-900 antialiased">

  <!-- NAVBAR -->
  <header class="sticky top-0 z-40 border-b border-slate-100 bg-white/80 backdrop-blur">
    <div class="mx-auto flex max-w-6xl items-center justify-between px-4 py-3 md:px-6">
      <!-- ChatGPT Image Dec 9, 2025, 06_18_15 PM.png -->
      <a href="#top" class="flex items-center gap-3">
        <div class="flex h-10 w-10 items-center justify-center rounded-2xl bg-gradient-to-br from-[var(--brand-green)] via-[var(--brand-yellow)] to-[var(--brand-red)]">
          <span class="text-xs font-black text-white">FP</span>
        </div>
        <div class="leading-tight">
          <div class="text-sm font-semibold text-slate-900">
            Integrated Safety &amp; Leadership
          </div>
          <div class="text-[0.7rem] text-slate-500">
            People. Preparedness. Protection.
          </div>
        </div>
      </a>

      <!-- Desktop nav -->
      <nav class="hidden items-center gap-6 text-sm text-slate-700 md:flex">
        <a href="#services" class="hover:text-slate-900">Services</a>
        <a href="#process" class="hover:text-slate-900">How It Works</a>
        <a href="#about" class="hover:text-slate-900">About</a>
        <a href="#proof" class="hover:text-slate-900">Results</a>
        <a href="#contact" class="hover:text-slate-900">Contact</a>
        <a href="#book" class="btn-primary">Book AHA Training</a>
      </nav>

      <!-- Mobile button -->
      <button id="navToggle" class="inline-flex items-center rounded-lg border border-slate-200 p-2 text-slate-700 md:hidden" aria-label="Open navigation">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </div>

    <!-- Mobile menu -->
    <div id="mobileNav" class="hidden border-t border-slate-100 bg-white md:hidden">
      <nav class="mx-auto flex max-w-6xl flex-col gap-2 px-4 py-4 text-sm text-slate-700">
        <a href="#services" class="py-1">Services</a>
        <a href="#process" class="py-1">How It Works</a>
        <a href="#about" class="py-1">About</a>
        <a href="#proof" class="py-1">Results</a>
        <a href="#contact" class="py-1">Contact</a>
        <a href="#book" class="mt-2 btn-primary text-center">Book AHA Training</a>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <main id="top">
    <section class="hero-bg">
      <div class="mx-auto grid max-w-6xl items-center gap-12 px-4 py-16 md:px-6 lg:grid-cols-[1.1fr,0.9fr] lg:py-20">
        <!-- Text -->
        <div>
          <div class="section-label mb-2">Indianapolis • Central Indiana</div>
          <h1 class="text-3xl font-black tracking-tight text-[var(--text-main)] sm:text-4xl lg:text-[2.75rem]">
            Turn compliance into a culture of safety, trust, and performance.
          </h1>
          <p class="mt-4 max-w-xl text-base text-slate-600 sm:text-lg">
            We blend <strong>American Heart Association training</strong>, <strong>EHS leadership</strong>, <strong>HR strategy</strong>, and
            <strong>executive coaching</strong> to build resilient organizations where people feel protected and prepared.
          </p>

          <div class="mt-6 flex flex-col gap-3 sm:flex-row sm:items-center">
            <a href="#book" class="btn-primary text-center">Book On-Site AHA CPR/AED</a>
            <a href="#contact" class="btn-ghost text-center">Request a Strategy Call</a>
          </div>

          <div class="mt-6 flex flex-wrap items-center gap-3 text-xs text-slate-500">
            <span class="pill">
              <span class="pill-dot"></span>
              SPHR • CSP • PMP • CHMM • PhD Leadership
            </span>
            <span class="pill bg-white border border-slate-200">
              15+ years in EHS &amp; HR leadership
            </span>
          </div>
        </div>

        <!-- Visual / card -->
        <div class="card-soft relative px-6 py-6 sm:px-8 sm:py-8">
          <!-- ChatGPT Image Dec 9, 2025, 06_18_15 PM.png -->
          <div class="flex items-center gap-3">
            <!-- Replace src with your final ChatGPT Image Dec 9, 2025, 06_18_15 PM.png file -->
            <div class="flex h-14 w-14 items-center justify-center rounded-2xl bg-gradient-to-br from-[var(--brand-green)] via-[var(--brand-yellow)] to-[var(--brand-red)]">
              <span class="text-xs font-black text-white">ChatGPT Image Dec 9, 2025, 06_18_15 PM.png</span>
            </div>
            <div class="text-sm text-slate-700">
              <div class="font-semibold">People. Preparedness. Protection.</div>
              <div class="text-xs text-slate-500">
                A single partner for safety, HR &amp; leadership.
              </div>
            </div>
          </div>

          <div class="mt-6 grid gap-4 text-sm">
            <div class="flex gap-3">
              <div class="mt-1 h-7 w-7 flex-none rounded-full bg-[var(--brand-green)]/10 text-[var(--brand-green)] flex items-center justify-center text-xs font-bold">
                1
              </div>
              <div>
                <div class="font-semibold">Start with AHA CPR/AED training</div>
                <p class="text-slate-600 text-xs mt-1">
                  BLS for Healthcare Providers, Heartsaver CPR/AED, First Aid, and AED program support delivered on-site.
                </p>
              </div>
            </div>

            <div class="flex gap-3">
              <div class="mt-1 h-7 w-7 flex-none rounded-full bg-[var(--brand-yellow)]/15 text-[var(--brand-yellow)] flex items-center justify-center text-xs font-bold">
                2
              </div>
              <div>
                <div class="font-semibold">Assess safety, HR &amp; culture gaps</div>
                <p class="text-slate-600 text-xs mt-1">
                  Practical assessments across OSHA/ANSI/NFPA, HR risk, and leadership behaviors that drive safety culture.
                </p>
              </div>
            </div>

            <div class="flex gap-3">
              <div class="mt-1 h-7 w-7 flex-none rounded-full bg-[var(--brand-red)]/10 text-[var(--brand-red)] flex items-center justify-center text-xs font-bold">
                3
              </div>
              <div>
                <div class="font-semibold">Build a resilient operating system</div>
                <p class="text-slate-600 text-xs mt-1">
                  Integrated programs that connect EHS, HR, and leadership into one people-centered, data-informed ecosystem.
                </p>
              </div>
            </div>
          </div>

          <div class="mt-5 rounded-xl bg-[var(--brand-cream)] px-4 py-3 text-xs text-slate-700">
            “Safety is not just a checklist problem—it’s a leadership problem. We help you solve both.”
          </div>
        </div>
      </div>
    </section>

    <!-- CREDENTIALS STRIP -->
    <section class="border-y border-slate-100 bg-slate-50/60">
      <div class="mx-auto flex max-w-6xl flex-wrap items-center justify-between gap-4 px-4 py-4 text-[0.7rem] uppercase tracking-[0.18em] text-slate-500 md:px-6">
        <div>PhD Organizational Leadership</div>
        <div>SPHR • Senior Professional in HR</div>
        <div>CSP • Certified Safety Professional</div>
        <div>PMP • Project Management Professional</div>
        <div>CHMM • Hazardous Materials Management</div>
      </div>
    </section>

    <!-- SERVICES -->
    <section id="services" class="bg-white">
      <div class="mx-auto max-w-6xl px-4 py-16 md:px-6 lg:py-20">
        <p class="section-label">Services</p>
        <div class="mt-2 flex flex-wrap items-end justify-between gap-4">
          <h2 class="text-2xl font-bold text-slate-900 sm:text-3xl">
            One partner for training, compliance, and leadership.
          </h2>
          <p class="max-w-md text-sm text-slate-600">
            Start where you need immediate help—CPR, safety programs, HR risk—or build a full roadmap that connects them all.
          </p>
        </div>

        <div class="mt-8 grid gap-6 md:grid-cols-2 lg:grid-cols-3">
          <!-- AHA TRAINING -->
          <article class="card-soft p-6">
            <div class="text-xs font-semibold uppercase tracking-[0.16em] text-[var(--brand-green)]">Entry Pathway</div>
            <h3 class="mt-2 text-lg font-semibold text-slate-900">AHA CPR/AED &amp; First Aid Training</h3>
            <p class="mt-2 text-sm text-slate-600">
              American Heart Association courses for healthcare providers, corporate teams, schools, and community groups.
            </p>
            <ul class="mt-3 space-y-1 text-xs text-slate-600">
              <li>• BLS for Healthcare Providers</li>
              <li>• Heartsaver CPR/AED &amp; First Aid</li>
              <li>• AED program setup &amp; basic compliance support</li>
            </ul>
            <a href="#book" class="mt-4 inline-block text-xs font-semibold text-[var(--brand-green)] hover:text-emerald-700">
              Book an on-site class &rarr;
            </a>
          </article>

          <!-- EHS -->
          <article class="card-soft p-6">
            <div class="text-xs font-semibold uppercase tracking-[0.16em] text-[var(--brand-yellow)]">Safety Leadership</div>
            <h3 class="mt-2 text-lg font-semibold text-slate-900">Environmental Health &amp; Safety Consulting</h3>
            <p class="mt-2 text-sm text-slate-600">
              CSP-led safety systems that move beyond checklists into culture and accountability.
            </p>
            <ul class="mt-3 space-y-1 text-xs text-slate-600">
              <li>• OSHA/ANSI/NFPA compliance reviews</li>
              <li>• Safety program design &amp; audits</li>
              <li>• Hazardous materials (CHMM) &amp; emergency planning</li>
            </ul>
            <a href="#contact" class="mt-4 inline-block text-xs font-semibold text-[var(--brand-yellow)] hover:text-amber-700">
              Discuss your safety program &rarr;
            </a>
          </article>

          <!-- HR -->
          <article class="card-soft p-6">
            <div class="text-xs font-semibold uppercase tracking-[0.16em] text-[var(--brand-red)]">People &amp; Culture</div>
            <h3 class="mt-2 text-lg font-semibold text-slate-900">HR &amp; People Operations Advisory</h3>
            <p class="mt-2 text-sm text-slate-600">
              SPHR-level HR strategy that aligns policies, employee relations, and safety expectations.
            </p>
            <ul class="mt-3 space-y-1 text-xs text-slate-600">
              <li>• HR compliance &amp; handbook audits</li>
              <li>• Employee relations &amp; investigations</li>
              <li>• Integrated HR–EHS culture frameworks</li>
            </ul>
            <a href="#contact" class="mt-4 inline-block text-xs font-semibold text-[var(--brand-red)] hover:text-red-700">
              Reduce HR risk &rarr;
            </a>
          </article>

          <!-- LEADERSHIP -->
          <article class="card-soft p-6 md:col-span-2 lg:col-span-1">
            <div class="text-xs font-semibold uppercase tracking-[0.16em] text-slate-500">Executive Coaching</div>
            <h3 class="mt-2 text-lg font-semibold text-slate-900">Leadership &amp; Culture Transformation</h3>
            <p class="mt-2 text-sm text-slate-600">
              PhD-backed coaching rooted in Emotional Intelligence and Transformational Leadership, tailored for safety-critical organizations.
            </p>
            <ul class="mt-3 space-y-1 text-xs text-slate-600">
              <li>• 1:1 executive coaching</li>
              <li>• Frontline supervisor &amp; safety leader academies</li>
              <li>• Culture diagnostics &amp; change roadmaps</li>
            </ul>
          </article>
        </div>
      </div>
    </section>

    <!-- PROCESS -->
    <section id="process" class="bg-[var(--brand-cream)]">
      <div class="mx-auto max-w-6xl px-4 py-16 md:px-6 lg:py-20">
        <p class="section-label">How We Work</p>
        <h2 class="mt-2 text-2xl font-bold text-slate-900 sm:text-3xl">
          A simple path from “check-the-box” compliance to resilient culture.
        </h2>

        <div class="mt-8 grid gap-8 md:grid-cols-3">
          <div>
            <div class="h-9 w-9 rounded-full bg-[var(--brand-green)]/10 text-[var(--brand-green)] flex items-center justify-center text-sm font-bold">
              1
            </div>
            <h3 class="mt-3 text-base font-semibold text-slate-900">Discover</h3>
            <p class="mt-2 text-sm text-slate-600">
              Clarify your regulatory requirements, current pain points, and leadership goals in a focused strategy session.
            </p>
          </div>

          <div>
            <div class="h-9 w-9 rounded-full bg-[var(--brand-yellow)]/15 text-[var(--brand-yellow)] flex items-center justify-center text-sm font-bold">
              2
            </div>
            <h3 class="mt-3 text-base font-semibold text-slate-900">Diagnose</h3>
            <p class="mt-2 text-sm text-slate-600">
              We assess EHS programs, HR risk, and leadership behaviors as one integrated system—not separate silos.
            </p>
          </div>

          <div>
            <div class="h-9 w-9 rounded-full bg-[var(--brand-red)]/10 text-[var(--brand-red)] flex items-center justify-center text-sm font-bold">
              3
            </div>
            <h3 class="mt-3 text-base font-semibold text-slate-900">Deliver</h3>
            <p class="mt-2 text-sm text-slate-600">
              You receive a prioritized roadmap plus training, coaching, and implementation support to make change stick.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- ABOUT / FOUNDER -->
    <section id="about" class="bg-white">
      <div class="mx-auto grid max-w-6xl items-center gap-10 px-4 py-16 md:px-6 lg:grid-cols-[1.2fr,0.8fr] lg:py-20">
        <div>
          <p class="section-label">Meet the Founder</p>
          <h2 class="mt-2 text-2xl font-bold text-slate-900 sm:text-3xl">
            Leadership, safety, and HR expertise in one seat at the table.
          </h2>
          <p class="mt-4 text-sm text-slate-600">
            Dr. Pams brings together doctoral research in leadership, an MBA in global operations, and over 15 years of
            hands-on experience leading EHS and HR programs for major organizations.
          </p>
          <ul class="mt-4 space-y-2 text-sm text-slate-700">
            <li>• PhD in Organizational Leadership — focus on Emotional Intelligence &amp; Transformational Leadership</li>
            <li>• MBA in Global Operations — strategy, execution, and systems thinking</li>
            <li>• SPHR, CSP, PMP, CHMM, CSM — multidisciplinary credibility in HR, safety, and project delivery</li>
          </ul>
          <p class="mt-4 text-sm text-slate-600">
            His philosophy is simple: <strong>“Safety culture is not just a compliance problem; it’s a leadership problem.”</strong>
            Our work helps your organization solve both.
          </p>
        </div>

        <div class="card-soft flex flex-col items-center px-6 py-8 text-center">
          <!-- Replace with your real headshot -->
          <div class="h-28 w-28 overflow-hidden rounded-full bg-slate-200">
            <img src="/assets/founder.jpg" alt="Dr. Pams" class="h-full w-full object-cover" />
          </div>
          <div class="mt-4 text-base font-semibold text-slate-900">Dr. Pams, PhD, MBA</div>
          <div class="text-xs font-medium uppercase tracking-[0.16em] text-slate-500">
            Safety • HR • Leadership
          </div>
          <p class="mt-3 text-xs text-slate-600">
            “Clients don’t need ten vendors. They need one trusted advisor who understands people, regulations, and operations.”
          </p>
        </div>
      </div>
    </section>

    <!-- PROOF / TESTIMONIALS -->
    <section id="proof" class="bg-slate-50">
      <div class="mx-auto max-w-6xl px-4 py-16 md:px-6 lg:py-20">
        <p class="section-label">Impact</p>
        <h2 class="mt-2 text-2xl font-bold text-slate-900 sm:text-3xl">
          What organizations gain from integrated safety &amp; leadership.
        </h2>

        <div class="mt-8 grid gap-6 md:grid-cols-3">
          <div class="card-soft p-5 text-sm">
            <h3 class="font-semibold text-slate-900">Fewer incidents</h3>
            <p class="mt-2 text-slate-600 text-xs">
              Clear expectations, better training, and active safety leadership result in fewer injuries and near-misses.
            </p>
          </div>
          <div class="card-soft p-5 text-sm">
            <h3 class="font-semibold text-slate-900">Lower HR &amp; legal risk</h3>
            <p class="mt-2 text-slate-600 text-xs">
              SPHR-level policies, documentation, and investigations reduce exposure while protecting both people and the business.
            </p>
          </div>
          <div class="card-soft p-5 text-sm">
            <h3 class="font-semibold text-slate-900">Stronger leadership bench</h3>
            <p class="mt-2 text-slate-600 text-xs">
              Coaching and development create leaders who communicate clearly, act decisively, and model safe, respectful behavior.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- CONTACT / BOOK -->
    <section id="contact" class="bg-white">
      <div class="mx-auto grid max-w-6xl gap-10 px-4 py-16 md:px-6 lg:grid-cols-[1.1fr,0.9fr] lg:py-20">
        <div>
          <p class="section-label">Get Started</p>
          <h2 class="mt-2 text-2xl font-bold text-slate-900 sm:text-3xl">
            Start with what matters most: protecting people.
          </h2>
          <p class="mt-4 text-sm text-slate-600">
            Use the form to request an on-site AHA class or a 20-minute strategy call. We’ll respond within one business day with
            options tailored to your organization.
          </p>
          <div class="mt-6 space-y-2 text-sm text-slate-700">
            <div><strong>Email:</strong> <a href="mailto:visiondriver.pro@gmail.com" class="text-[var(--brand-green)] hover:underline">visiondriver.pro@gmail.com</a></div>
            <div><strong>Phone:</strong> <a href="tel:+18323439970" class="text-[var(--brand-green)] hover:underline">(832) 343-9970</a></div>
            <div><strong>Location:</strong> Indianapolis, IN (serving Central Indiana)</div>
          </div>
        </div>

        <form id="contactForm" class="card-soft space-y-4 px-5 py-6">
          <div>
            <label class="block text-xs font-semibold text-slate-700">Full name</label>
            <input name="name" required class="mt-1 w-full rounded-lg border border-slate-200 px-3 py-2 text-sm shadow-sm focus:border-[var(--brand-green)] focus:outline-none" />
          </div>

          <div class="grid gap-4 sm:grid-cols-2">
            <div>
              <label class="block text-xs font-semibold text-slate-700">Email</label>
              <input type="email" name="email" required class="mt-1 w-full rounded-lg border border-slate-200 px-3 py-2 text-sm shadow-sm focus:border-[var(--brand-green)] focus:outline-none" />
            </div>
            <div>
              <label class="block text-xs font-semibold text-slate-700">Phone</label>
              <input name="phone" class="mt-1 w-full rounded-lg border border-slate-200 px-3 py-2 text-sm shadow-sm focus:border-[var(--brand-green)] focus:outline-none" />
            </div>
          </div>

          <div>
            <label class="block text-xs font-semibold text-slate-700">Organization</label>
            <input name="org" class="mt-1 w-full rounded-lg border border-slate-200 px-3 py-2 text-sm shadow-sm focus:border-[var(--brand-green)] focus:outline-none" />
          </div>

          <div>
            <label class="block text-xs font-semibold text-slate-700">I’m interested in</label>
            <select name="interest" class="mt-1 w-full rounded-lg border border-slate-200 px-3 py-2 text-sm shadow-sm focus:border-[var(--brand-green)] focus:outline-none">
              <option>AHA CPR/AED training</option>
              <option>Safety / EHS consulting</option>
              <option>HR &amp; people operations advisory</option>
              <option>Leadership coaching &amp; culture</option>
              <option>Integrated, long-term partnership</option>
            </select>
          </div>

          <div>
            <label class="block text-xs font-semibold text-slate-700">Message</label>
            <textarea name="message" rows="4" class="mt-1 w-full rounded-lg border border-slate-200 px-3 py-2 text-sm shadow-sm focus:border-[var(--brand-green)] focus:outline-none" placeholder="Tell us briefly about your goals and timelines."></textarea>
          </div>

          <div class="flex flex-col gap-3 sm:flex-row sm:items-center sm:justify-between">
            <button type="submit" class="btn-primary w-full sm:w-auto">Send message</button>
            <p id="formStatus" class="text-xs text-slate-500">No spam. We only use your details to respond to this inquiry.</p>
          </div>
        </form>
      </div>
    </section>

    <!-- Bottom CTA -->
    <section id="book" class="bg-gradient-to-r from-[var(--brand-green)] via-[var(--brand-yellow)] to-[var(--brand-red)]">
      <div class="mx-auto max-w-6xl px-4 py-8 md:px-6">
        <div class="card-soft flex flex-col items-center justify-between gap-4 bg-white/95 px-6 py-6 text-center sm:flex-row sm:text-left">
          <div>
            <h2 class="text-lg font-semibold text-slate-900">
              Ready to bring AHA CPR/AED training on-site?
            </h2>
            <p class="mt-1 text-xs text-slate-600">
              Equip your teams with life-saving skills and open the door to a strategic safety &amp; leadership partnership.
            </p>
          </div>
          <a href="#contact" class="btn-primary">Request dates &amp; pricing</a>
        </div>
      </div>
    </section>
  </main>

  <!-- FOOTER -->
  <footer class="border-t border-slate-100 bg-slate-50">
    <div class="mx-auto flex max-w-6xl flex-col items-center justify-between gap-3 px-4 py-6 text-xs text-slate-500 md:flex-row md:px-6">
      <div>© 2025 Integrated Safety &amp; Leadership Solutions. All rights reserved.</div>
      <div class="flex gap-4">
        <a href="#" class="hover:underline">Privacy</a>
        <a href="#" class="hover:underline">Terms</a>
      </div>
    </div>
  </footer>

  <script>
    // Mobile nav toggle
    const navToggle = document.getElementById('navToggle');
    const mobileNav = document.getElementById('mobileNav');
    if (navToggle && mobileNav) {
      navToggle.addEventListener('click', () => {
        mobileNav.classList.toggle('hidden');
      });
    }

    // Simple fake form handler
    const contactForm = document.getElementById('contactForm');
    const formStatus = document.getElementById('formStatus');
    if (contactForm) {
      contactForm.addEventListener('submit', function (e) {
        e.preventDefault();
        if (formStatus) {
          formStatus.textContent = "Thank you! Your message has been received. We’ll respond within one business day.";
          formStatus.classList.remove('text-slate-500');
          formStatus.classList.add('text-[var(--brand-green)]');
        }
        contactForm.reset();
      });
    }
  </script>
</body>
</html>
