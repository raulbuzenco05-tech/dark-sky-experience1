# dark-sky-experience1
export default function DarkSkyExperienceWeb() {
  const posts = [
    {
      title: "Qué ver en el Montsec de noche: guía completa",
      excerpt:
        "Descubre por qué el Montsec es uno de los mejores lugares para observar estrellas y vivir una escapada astronómica inolvidable.",
    },
    {
      title: "Cómo identificar constelaciones fácilmente",
      excerpt:
        "Una guía sencilla para iniciarse en la observación del cielo y reconocer las principales constelaciones visibles durante el año.",
    },
    {
      title: "Los mejores lugares para ver estrellas en España",
      excerpt:
        "Comparativa de destinos de turismo astronómico y razones por las que el Montsec destaca como una opción diferencial.",
    },
    {
      title: "Turismo astronómico: una nueva forma de viajar",
      excerpt:
        "El auge de las experiencias inmersivas, sostenibles y personalizadas ha convertido el cielo nocturno en un nuevo recurso turístico.",
    },
    {
      title: "Escapada romántica bajo las estrellas",
      excerpt:
        "Una propuesta pensada para parejas que buscan exclusividad, tranquilidad y una experiencia distinta en plena naturaleza.",
    },
  ];

  const suites = [
    {
      title: "Sky Dome Suite",
      text: "Cúpula panorámica con diseño exclusivo, vistas abiertas al firmamento y ambiente de máxima privacidad.",
    },
    {
      title: "Celestial Dinner",
      text: "Cena privada bajo las estrellas con servicio premium, iluminación tenue y selección gastronómica cuidada.",
    },
    {
      title: "Private Stargazing",
      text: "Sesión astronómica personalizada con telescopio y acompañamiento experto para una vivencia más exclusiva.",
    },
  ];

  const highlights = [
    "Suites astronómicas de lujo",
    "Experiencias privadas y personalizadas",
    "Reserva directa en la web oficial",
    "Contenidos exclusivos mediante QR",
  ];

  return (
    <div className="min-h-screen bg-[#06070a] text-[#f6f1e8]">
      <header className="relative overflow-hidden border-b border-white/10">
        <div className="absolute inset-0 bg-[radial-gradient(circle_at_top,_rgba(212,175,55,0.16),_transparent_32%),radial-gradient(circle_at_80%_20%,_rgba(255,255,255,0.08),_transparent_22%),linear-gradient(to_bottom,_rgba(6,7,10,0.55),_rgba(6,7,10,0.96))]" />
        <div className="absolute inset-0 opacity-30 bg-[linear-gradient(rgba(255,255,255,0.03)_1px,transparent_1px),linear-gradient(90deg,rgba(255,255,255,0.03)_1px,transparent_1px)] bg-[size:42px_42px]" />

        <div className="relative max-w-7xl mx-auto px-6 py-10 lg:py-12">
          <nav className="flex items-center justify-between">
            <div>
              <p className="text-xs uppercase tracking-[0.45em] text-[#d4af37]">Dark Sky Experience</p>
              <p className="text-sm text-[#d9d0c0] mt-2">Luxury Astronomical Retreat · Montsec</p>
            </div>
            <div className="hidden md:flex items-center gap-8 text-sm text-[#d9d0c0]">
              <a href="#concept" className="hover:text-white transition">Concepto</a>
              <a href="#suites" className="hover:text-white transition">Suites</a>
              <a href="#blog" className="hover:text-white transition">Blog</a>
              <a href="#reserve" className="hover:text-white transition">Reservas</a>
            </div>
          </nav>
        </div>

        <div className="relative max-w-7xl mx-auto px-6 pb-24 pt-10 lg:pt-16 lg:pb-32">
          <div className="grid lg:grid-cols-[1.1fr_0.9fr] gap-14 items-center">
            <div>
              <p className="inline-flex items-center rounded-full border border-[#d4af37]/30 bg-[#d4af37]/10 px-4 py-2 text-sm text-[#f0df9a] mb-8">
                Turismo astronómico inmersivo de alta gama
              </p>
              <h1 className="text-5xl md:text-6xl xl:text-7xl font-semibold leading-[1.05] tracking-tight max-w-4xl">
                Una experiencia de lujo diseñada para dormir bajo uno de los cielos más puros de Europa.
              </h1>
              <p className="text-lg md:text-xl text-[#d9d0c0] mt-8 max-w-2xl leading-9">
                Dark Sky Experience redefine el alojamiento experiencial a través de suites astronómicas exclusivas,
                observación privada del firmamento y un entorno donde diseño, silencio y naturaleza se integran en una
                misma propuesta premium.
              </p>
              <div className="flex flex-wrap gap-4 mt-10">
                <a
                  href="#reserve"
                  className="rounded-full bg-[#d4af37] text-black px-7 py-3.5 font-medium shadow-2xl hover:-translate-y-0.5 transition"
                >
                  Reservar estancia
                </a>
                <a
                  href="#blog"
                  className="rounded-full border border-white/15 px-7 py-3.5 font-medium text-[#f6f1e8] hover:bg-white/5 transition"
                >
                  Explorar el blog
                </a>
              </div>

              <div className="grid sm:grid-cols-2 gap-4 mt-12 max-w-2xl">
                {highlights.map((item) => (
                  <div key={item} className="rounded-2xl border border-white/10 bg-white/[0.04] px-5 py-4 backdrop-blur-sm">
                    <p className="text-sm text-[#efe7d8]">{item}</p>
                  </div>
                ))}
              </div>
            </div>

            <div className="relative">
              <div className="absolute -inset-6 rounded-[2.5rem] bg-[#d4af37]/10 blur-3xl" />
              <div className="relative rounded-[2.5rem] border border-white/10 bg-gradient-to-br from-white/[0.08] to-white/[0.03] p-4 shadow-[0_40px_120px_rgba(0,0,0,0.55)] backdrop-blur-md">
                <div className="rounded-[2rem] border border-white/10 bg-[linear-gradient(160deg,rgba(255,255,255,0.08),rgba(255,255,255,0.02))] p-8 min-h-[540px] flex flex-col justify-between">
                  <div>
                    <p className="text-xs uppercase tracking-[0.45em] text-[#d4af37]">Signature Stay</p>
                    <h2 className="text-4xl font-semibold mt-5 leading-tight">Sky Dome Suite</h2>
                    <p className="text-[#d9d0c0] mt-6 leading-8 text-lg">
                      Una cúpula panorámica de alta gama concebida para ofrecer privacidad, confort y contemplación.
                      Su diseño integra paisaje, astronomía y hospitalidad premium en una estancia exclusiva.
                    </p>
                  </div>
                  <div className="grid grid-cols-2 gap-4 mt-10">
                    <div className="rounded-2xl border border-white/10 bg-black/20 p-5">
                      <p className="text-3xl font-semibold text-[#d4af37]">5</p>
                      <p className="text-sm text-[#d9d0c0] mt-2">entradas iniciales del blog</p>
                    </div>
                    <div className="rounded-2xl border border-white/10 bg-black/20 p-5">
                      <p className="text-3xl font-semibold text-[#d4af37]">Direct</p>
                      <p className="text-sm text-[#d9d0c0] mt-2">booking experience</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </header>

      <main className="max-w-7xl mx-auto px-6 pb-28">
        <section id="concept" className="py-24">
          <div className="grid lg:grid-cols-[0.95fr_1.05fr] gap-14 items-start">
            <div>
              <p className="text-xs uppercase tracking-[0.45em] text-[#d4af37] mb-5">Concepto</p>
              <h2 className="text-4xl md:text-5xl font-semibold leading-tight">
                Una web premium que informa, seduce y convierte.
              </h2>
            </div>
            <div>
              <p className="text-[#d9d0c0] text-lg leading-9">
                La página web se plantea como el principal activo digital del negocio. Su función es presentar la propuesta
                de valor, reforzar el posicionamiento de marca y facilitar la reserva directa. No actúa únicamente como un
                escaparate, sino como una herramienta estratégica de captación, venta y fidelización.
              </p>
              <div className="mt-8 rounded-[2rem] border border-white/10 bg-white/[0.03] p-7">
                <p className="text-sm uppercase tracking-[0.35em] text-[#d4af37] mb-4">Propuesta de valor</p>
                <p className="text-[#efe7d8] leading-8">
                  Alojamiento exclusivo, observación privada del cielo nocturno, contenidos digitales vinculados a la
                  experiencia y un blog corporativo diseñado para posicionar palabras clave relacionadas con turismo
                  astronómico, Montsec y escapadas bajo las estrellas.
                </p>
              </div>
            </div>
          </div>
        </section>

        <section id="suites" className="py-24 border-t border-white/10">
          <div className="flex flex-col lg:flex-row lg:items-end lg:justify-between gap-6 mb-12">
            <div>
              <p className="text-xs uppercase tracking-[0.45em] text-[#d4af37] mb-5">Suites & Experiences</p>
              <h2 className="text-4xl md:text-5xl font-semibold leading-tight max-w-3xl">
                El alojamiento deja de ser un servicio básico para convertirse en una experiencia de lujo.
              </h2>
            </div>
            <p className="text-[#d9d0c0] max-w-xl text-lg leading-9">
              Cada sección de la web está orientada a comunicar exclusividad, personalización y alta calidad, reforzando
              la identidad premium del negocio.
            </p>
          </div>

          <div className="grid md:grid-cols-3 gap-6">
            {suites.map((item) => (
              <div key={item.title} className="rounded-[2rem] border border-white/10 bg-[linear-gradient(180deg,rgba(255,255,255,0.06),rgba(255,255,255,0.03))] p-8 shadow-[0_20px_80px_rgba(0,0,0,0.35)]">
                <p className="text-xs uppercase tracking-[0.35em] text-[#d4af37] mb-4">Exclusive</p>
                <h3 className="text-2xl font-semibold leading-tight">{item.title}</h3>
                <p className="text-[#d9d0c0] mt-5 leading-8">{item.text}</p>
              </div>
            ))}
          </div>
        </section>

        <section id="blog" className="py-24 border-t border-white/10">
          <div className="grid lg:grid-cols-[0.85fr_1.15fr] gap-12 mb-12">
            <div>
              <p className="text-xs uppercase tracking-[0.45em] text-[#d4af37] mb-5">Blog corporativo</p>
              <h2 className="text-4xl md:text-5xl font-semibold leading-tight">
                Contenido editorial para posicionar y proyectar autoridad de marca.
              </h2>
            </div>
            <p className="text-[#d9d0c0] text-lg leading-9">
              El blog se integra dentro de la estrategia SEO del negocio y actúa como herramienta de captación de tráfico
              cualificado. Sus publicaciones responden a búsquedas relacionadas con observación de estrellas, turismo
              astronómico y experiencias en el Montsec.
            </p>
          </div>

          <div className="grid md:grid-cols-2 xl:grid-cols-3 gap-6">
            {posts.map((post, index) => (
              <article key={post.title} className="rounded-[2rem] border border-white/10 bg-white/[0.04] p-7 hover:bg-white/[0.06] transition shadow-[0_20px_60px_rgba(0,0,0,0.28)]">
                <p className="text-xs uppercase tracking-[0.35em] text-[#d4af37] mb-4">Journal {index + 1}</p>
                <h3 className="text-2xl font-semibold leading-tight">{post.title}</h3>
                <p className="text-[#d9d0c0] mt-5 leading-8">{post.excerpt}</p>
                <button className="mt-6 text-[#f6f1e8] border-b border-[#d4af37]/70 pb-1">Leer entrada</button>
              </article>
            ))}
          </div>
        </section>

        <section id="reserve" className="py-24 border-t border-white/10">
          <div className="rounded-[2.5rem] border border-[#d4af37]/20 bg-[linear-gradient(145deg,rgba(212,175,55,0.10),rgba(255,255,255,0.03),rgba(6,7,10,0.95))] p-8 md:p-12 shadow-[0_40px_140px_rgba(0,0,0,0.5)]">
            <div className="grid lg:grid-cols-[0.95fr_1.05fr] gap-12 items-center">
              <div>
                <p className="text-xs uppercase tracking-[0.45em] text-[#d4af37] mb-5">Reservas</p>
                <h2 className="text-4xl md:text-5xl font-semibold leading-tight">
                  Diseñada para transformar interés en reserva directa.
                </h2>
                <p className="text-[#d9d0c0] text-lg leading-9 mt-6 max-w-xl">
                  Esta sección concentra la conversión principal de la web. Presenta disponibilidad, preferencias del
                  cliente y una experiencia de contacto cuidada, acorde con el posicionamiento luxury del establecimiento.
                </p>
              </div>

              <form className="grid gap-4 rounded-[2rem] border border-white/10 bg-black/25 p-7 backdrop-blur-md">
                <input className="rounded-2xl bg-white/[0.05] border border-white/10 px-5 py-4 outline-none placeholder:text-[#b9ae9c]" placeholder="Nombre completo" />
                <input className="rounded-2xl bg-white/[0.05] border border-white/10 px-5 py-4 outline-none placeholder:text-[#b9ae9c]" placeholder="Correo electrónico" />
                <div className="grid sm:grid-cols-2 gap-4">
                  <input className="rounded-2xl bg-white/[0.05] border border-white/10 px-5 py-4 outline-none placeholder:text-[#b9ae9c]" placeholder="Fecha de llegada" />
                  <input className="rounded-2xl bg-white/[0.05] border border-white/10 px-5 py-4 outline-none placeholder:text-[#b9ae9c]" placeholder="Fecha de salida" />
                </div>
                <textarea className="rounded-2xl bg-white/[0.05] border border-white/10 px-5 py-4 outline-none min-h-[130px] placeholder:text-[#b9ae9c]" placeholder="Indica si deseas una experiencia romántica, observación privada o preferencias especiales" />
                <button type="button" className="rounded-full bg-[#d4af37] text-black px-6 py-3.5 font-medium hover:-translate-y-0.5 transition">
                  Solicitar disponibilidad
                </button>
              </form>
            </div>
          </div>
        </section>
      </main>
    </div>
  );
}
