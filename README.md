<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GAP - Renta de Rompedoras</title>
    <style>
        :root { --naranja: #ff6600; --negro: #222; --gris: #f4f4f4; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; color: #333; }
        
        header { background: var(--negro); color: white; padding: 1rem; text-align: center; }
        .hero { 
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1581094288338-2314dddb7ee1?auto=format&fit=crop&q=80&w=1000') center/cover;
            height: 400px; color: white; display: flex; flex-direction: column; 
            justify-content: center; align-items: center; text-align: center;
        }
        
        .btn-whatsapp { 
            background: #25d366; color: white; padding: 15px 30px; 
            text-decoration: none; border-radius: 50px; font-weight: bold; font-size: 1.2rem;
        }

        .catalogo { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; padding: 40px; }
        .card { border: 1px solid #ddd; padding: 20px; border-radius: 8px; text-align: center; background: var(--gris); }
        .card h3 { color: var(--naranja); }
        
        footer { background: var(--negro); color: white; text-align: center; padding: 20px; margin-top: 40px; }
    </style>
</head>
<body>

<header>
    <h1>GAP Maquinaria Ligera</h1>
</header>

<section class="hero">
    <h2>¿Necesitas demoler? Nosotros te ayudamos.</h2>
    <p>Renta de rompedoras eléctricas y neumáticas de alto rendimiento.</p><br>
    <a href="#" class="btn-whatsapp">Cotizar por WhatsApp</a>
</section>

<section class="catalogo">
    <div class="card">
        <h3>Rompedora 10kg</h3>
        <p>Ideal para muros y trabajos ligeros.</p>
        <p><strong>Desde $450 x día</strong></p>
    </div>
    <div class="card">
        <h3>Rompedora 30kg</h3>
        <p>Uso rudo para pisos de concreto y asfalto.</p>
        <p><strong>Desde $600 x día</strong></p>
    </div>
    <div class="card">
        <h3>Rotomartillos</h3>
        <p>Perforación y demolición precisa.</p>
        <p><strong>Desde $350 x día</strong></p>
    </div>
</section>

<footer>
    <p>&copy; 2026 GAP Renta de Rompedoras - Ubicados en Monterrey, NL</p>
</footer>

</body>
</html>
