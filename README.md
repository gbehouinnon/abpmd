# abpmd
ASSOCIATION BÉNINOISE POUR LA PRÉVENTION ET LA MÉDIATION DES DETTES ABPMD 
<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ABPMD | Médiation des Dettes au Bénin</title>
    
    <!-- Tailwind CSS pour un design professionnel -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Polices et Icônes -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: '#002B5B',
                        gold: '#D4A017',
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    
    <style>
        .hero-bg {
            background: linear-gradient(rgba(0, 43, 91, 0.9), rgba(0, 43, 91, 0.8)), 
                        url('https://images.unsplash.com/photo-1554224155-6726b3ff858f?auto=format&fit=crop&w=1411&q=80');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 font-sans">

    <!-- NAVIGATION -->
    <nav class="fixed w-full z-50 bg-white/90 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-6 h-20 flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <div class="bg-navy p-2 rounded-lg shadow-lg">
                    <i class="fas fa-scale-balanced text-white text-xl"></i>
                </div>
                <span class="text-2xl font-extrabold text-navy tracking-tighter">ABPMD</span>
            </div>
            <div class="hidden md:flex items-center space-x-8">
                <a href="#accueil" class="font-bold text-slate-600 hover:text-navy">Accueil</a>
                <a href="#fosir" class="font-bold text-slate-600 hover:text-navy font-bold">Lien FoSIR</a>
                <a href="#contact" class="bg-navy text-white px-6 py-2.5 rounded-full font-bold hover:bg-navy/90 transition shadow-lg shadow-navy/20">Nous Rejoindre</a>
            </div>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <header id="accueil" class="hero-bg min-h-screen flex items-center pt-20">
        <div class="max-w-7xl mx-auto px-6 w-full grid lg:grid-cols-2 gap-12 items-center">
            <div class="text-white">
                <span class="inline-block bg-gold/20 text-gold px-4 py-1 rounded-full text-sm font-bold mb-4 border border-gold/30">ASSOCIATION BÉNINOISE</span>
                <h1 class="text-5xl lg:text-7xl font-extrabold leading-tight mb-6">Restaurer la <span class="text-gold">Dignité</span> financière.</h1>
                <p class="text-xl text-slate-200 mb-10 max-w-xl">L'ABPMD accompagne les artisans et les citoyens béninois dans la médiation de leurs dettes pour une stabilité sociale durable.</p>
                <div class="flex flex-col sm:flex-row gap-4">
                    <a href="#contact" class="bg-gold text-navy px-8 py-4 rounded-xl font-bold text-center text-lg hover:scale-105 transition shadow-2xl shadow-gold/20">Devenir Membre Fondateur</a>
                    <a href="#fosir" class="bg-white/10 backdrop-blur border border-white/20 text-white px-8 py-4 rounded-xl font-bold text-center hover:bg-white/20 transition">Notre mission FoSIR</a>
                </div>
            </div>
        </div>
    </header>

    <!-- SECTION FOSIR -->
    <section id="fosir" class="py-24 bg-white px-6">
        <div class="max-w-7xl mx-auto bg-slate-50 rounded-[3rem] p-10 md:p-20 border border-slate-100 flex flex-col md:flex-row items-center gap-12">
            <div class="md:w-1/2">
                <h2 class="text-navy text-4xl font-black mb-6 uppercase leading-none">Synergie avec <br><span class="text-gold text-5xl">le FoSIR</span></h2>
                <p class="text-lg text-slate-600 mb-8 leading-relaxed">
                    Le <strong>Fonds de Soutien aux Initiatives Régionales (FoSIR)</strong> est le partenaire naturel de l'ABPMD. Nous sécurisons les financements octroyés par l'État en offrant une médiation professionnelle aux bénéficiaires en difficulté de remboursement.
                </p>
                <div class="flex items-center space-x-4 bg-white p-4 rounded-2xl shadow-sm border border-slate-100">
                    <i class="fas fa-handshake-alt text-gold text-3xl"></i>
                    <p class="font-bold text-navy">Appui technique à la résilience économique régionale.</p>
                </div>
            </div>
            <div class="md:w-1/2 grid grid-cols-2 gap-4">
                <div class="bg-white p-6 rounded-3xl shadow-sm border border-slate-100 text-center">
                    <i class="fas fa-shield-halved text-navy text-3xl mb-4"></i>
                    <p class="text-[10px] font-black text-slate-400 uppercase tracking-widest">Protection</p>
                </div>
                <div class="bg-white p-6 rounded-3xl shadow-sm border border-slate-100 text-center">
                    <i class="fas fa-gavel text-navy text-3xl mb-4"></i>
                    <p class="text-[10px] font-black text-slate-400 uppercase tracking-widest">Médiation</p>
                </div>
                <div class="bg-white p-6 rounded-3xl shadow-sm border border-slate-100 text-center">
                    <i class="fas fa-users-gear text-navy text-3xl mb-4"></i>
                    <p class="text-[10px] font-black text-slate-400 uppercase tracking-widest">Soutien Artisans</p>
                </div>
                <div class="bg-white p-6 rounded-3xl shadow-sm border border-slate-100 text-center">
                    <i class="fas fa-building-columns text-navy text-3xl mb-4"></i>
                    <p class="text-[10px] font-black text-slate-400 uppercase tracking-widest">Institutionnel</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="py-24 px-6 text-center">
        <h2 class="text-3xl font-black text-navy mb-12 uppercase tracking-tighter">Contactez le comité d'organisation</h2>
        <div class="max-w-2xl mx-auto bg-navy text-white p-12 rounded-[3rem] shadow-2xl relative overflow-hidden">
            <div class="relative z-10">
                <p class="text-gold font-bold mb-4 tracking-widest uppercase text-xs">Siège Social Provisoire</p>
                <p class="text-2xl font-bold mb-8">Cotonou, République du Bénin</p>
                <div class="space-y-4">
                    <div class="flex items-center justify-center space-x-3 bg-white/10 p-4 rounded-2xl">
                        <i class="fab fa-whatsapp text-2xl text-green-400"></i>
                        <span class="text-xl font-bold">[0144250009]</span>
                    </div>
                    <div class="flex items-center justify-center space-x-3 bg-white/10 p-4 rounded-2xl">
                        <i class="fas fa-envelope text-2xl text-gold"></i>
                        <span class="text-xl font-bold">contact@abpmd.bj</span>
                    </div>
                </div>
            </div>
            <div class="absolute -right-20 -bottom-20 w-64 h-64 bg-white/5 rounded-full"></div>
        </div>
    </section>

    <footer class="py-12 bg-slate-900 text-slate-500 text-center text-sm font-bold border-t border-slate-800">
        <p>&copy; 2024 ABPMD - Association Béninoise pour la Prévention et la Médiation des Dettes.</p>
        <p class="mt-2 text-gold opacity-50 uppercase text-[10px] tracking-[0.2em]">Paix Sociale • Médiation • Développement</p>
    </footer>

</body>
</html>
