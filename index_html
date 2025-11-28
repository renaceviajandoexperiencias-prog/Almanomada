<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Retiro Alma Nómada - Yoga y Transformación en Marruecos</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header */
        header {
            background: linear-gradient(135deg, #d4a574 0%, #a67c52 100%);
            color: white;
            padding: 80px 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="sand" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse"><path d="M0,10 Q5,8 10,10 T20,10" fill="none" stroke="rgba(255,255,255,0.1)" stroke-width="0.5"/></pattern></defs><rect width="100" height="100" fill="url(%23sand)"/></svg>');
            opacity: 0.3;
        }
        
        header > * {
            position: relative;
            z-index: 1;
        }
        
        .subtitle {
            font-size: 16px;
            margin-bottom: 20px;
            opacity: 0.95;
            letter-spacing: 2px;
        }
        
        h1 {
            font-size: 48px;
            margin-bottom: 15px;
            font-weight: 700;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }
        
        .tagline {
            font-size: 20px;
            margin-bottom: 30px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            font-weight: 300;
        }
        
        .dates {
            font-size: 18px;
            background: rgba(0,0,0,0.1);
            padding: 12px 20px;
            border-radius: 25px;
            display: inline-block;
            margin-bottom: 20px;
        }
        
        .cta-btn {
            background: white;
            color: #d4a574;
            padding: 14px 30px;
            border: none;
            border-radius: 25px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            margin: 10px 10px;
        }
        
        .cta-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
        }
        
        /* Secciones */
        section {
            padding: 60px 20px;
            border-bottom: 1px solid #e0e0e0;
        }
        
        section:nth-child(odd) {
            background: #f9f7f4;
        }
        
        h2 {
            font-size: 32px;
            margin-bottom: 20px;
            color: #a67c52;
            text-align: center;
        }
        
        .pain-section {
            background: linear-gradient(135deg, #fff5f0 0%, #ffe8e0 100%);
            padding: 50px 30px;
            border-radius: 10px;
            margin: 40px 0;
            border-left: 5px solid #d4a574;
        }
        
        .pain-section p {
            font-size: 18px;
            line-height: 2;
            color: #555;
            margin-bottom: 15px;
            font-weight: 300;
        }
        
        .vision-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 25px;
            margin: 30px 0;
        }
        
        .vision-item {
            padding: 20px;
            background: white;
            border-radius: 8px;
            border-left: 4px solid #d4a574;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }
        
        .vision-item p {
            font-size: 16px;
            color: #555;
        }
        
        .target-list {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 30px 0;
        }
        
        .target-item {
            padding: 15px;
            background: white;
            border-radius: 8px;
        }
        
        .target-item::before {
            content: '✔ ';
            color: #d4a574;
            font-weight: bold;
            margin-right: 8px;
        }
        
        .objection-item {
            background: white;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
            border-left: 4px solid #d4a574;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }
        
        .objection-item strong {
            color: #a67c52;
            display: block;
            margin-bottom: 10px;
        }
        
        .unique-feature {
            background: white;
            padding: 25px;
            margin: 15px 0;
            border-radius: 8px;
            border-top: 4px solid #d4a574;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }
        
        .feature-number {
            color: #d4a574;
            font-weight: bold;
            font-size: 20px;
            margin-bottom: 8px;
        }
        
        .itinerary {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 30px 0;
        }
        
        .day-card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            border-top: 4px solid #d4a574;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }
        
        .day-card h4 {
            color: #a67c52;
            margin-bottom: 10px;
        }
        
        .includes-list {
            margin: 30px 0;
        }
        
        .include-item {
            padding: 12px 15px;
            margin: 10px 0;
            background: white;
            border-radius: 5px;
            border-left: 4px solid #d4a574;
        }
        
        .include-item::before {
            content: '✔ ';
            color: #d4a574;
            font-weight: bold;
        }
        
        .not-include-item {
            padding: 12px 15px;
            margin: 10px 0;
            background: #f0f0f0;
            border-radius: 5px;
            border-left: 4px solid #ccc;
        }
        
        .not-include-item::before {
            content: '✕ ';
            color: #999;
            font-weight: bold;
        }
        
        .pricing-section {
            background: linear-gradient(135deg, #d4a574 0%, #a67c52 100%);
            color: white;
            padding: 40px;
            border-radius: 10px;
            text-align: center;
            margin: 40px 0;
        }
        
        .price-box {
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 10px;
            margin: 20px 0;
        }
        
        .price-label {
            font-size: 14px;
            opacity: 0.9;
            margin-bottom: 10px;
        }
        
        .price {
            font-size: 42px;
            font-weight: bold;
            margin: 15px 0;
        }
        
        .testimonial {
            background: white;
            padding: 30px;
            border-radius: 8px;
            border-left: 5px solid #d4a574;
            font-style: italic;
            margin: 30px 0;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }
        
        .author {
            font-style: normal;
            color: #a67c52;
            font-weight: 600;
            margin-top: 15px;
        }
        
        .about-rosa {
            background: linear-gradient(135deg, #fff5f0 0%, #ffe8e0 100%);
            padding: 40px;
            border-radius: 10px;
            margin: 30px 0;
        }
        
        .about-rosa p {
            font-size: 16px;
            line-height: 1.8;
            margin-bottom: 15px;
            color: #555;
        }
        
        .cta-section {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(135deg, #d4a574 0%, #a67c52 100%);
            color: white;
        }
        
        .cta-section h2 {
            color: white;
            font-size: 40px;
            margin-bottom: 30px;
        }
        
        .cta-buttons {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin-bottom: 30px;
        }
        
        .cta-btn-secondary {
            background: rgba(255,255,255,0.2);
            color: white;
            border: 2px solid white;
            padding: 12px 25px;
            border-radius: 25px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .cta-btn-secondary:hover {
            background: white;
            color: #d4a574;
        }
        
        .form-section {
            background: white;
            padding: 40px;
            border-radius: 10px;
            max-width: 500px;
            margin: 40px auto;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            color: #333;
            font-weight: 600;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-family: inherit;
            font-size: 14px;
            transition: border 0.3s;
        }
        
        .form-group input:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: #d4a574;
            box-shadow: 0 0 8px rgba(212, 165, 116, 0.2);
        }
        
        .submit-btn {
            width: 100%;
            padding: 14px;
            background: #d4a574;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .submit-btn:hover {
            background: #a67c52;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(212, 165, 116, 0.3);
        }
        
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 14px;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 32px;
            }
            
            .vision-grid,
            .target-list,
            .itinerary {
                grid-template-columns: 1fr;
            }
            
            .cta-buttons {
                flex-direction: column;
            }
            
            header {
                padding: 50px 20px;
            }
        }
    </style>
</head>
<body>
    <!-- HEADER -->
    <header>
        <div class="subtitle">MARRUECOS • SAHARA • YOGA • RECONEXIÓN INTERIOR</div>
        <h1>Retiro Alma Nómada</h1>
        <p class="tagline">Yoga y Transformación en Marruecos</p>
        <div class="dates">📅 09 - 15 FEBRERO</div>
        <p style="margin-top: 20px; font-size: 18px;">7 días para reconectar contigo, encontrar claridad y sentirte sostenida por una tribu íntima… sin sentirte sola ni un minuto.</p>
        <button class="cta-btn" onclick="scrollToForm()">QUIERO RESERVAR MI PLAZA</button>
    </header>

    <div class="container">
        <!-- BLOQUE 2: EL DOLOR COTIDIANO -->
        <section>
            <h2>¿Cuándo fue la última vez que respiraste de verdad?</h2>
            <div class="pain-section">
                <p>Despiertas, cumples, sostienes, trabajas, duermes.</p>
                <p><strong>Repites.</strong></p>
                <p>Y mientras tanto, una parte de ti pide a gritos un respiro.</p>
                <p>Sabes que necesitas parar.</p>
                <p>Sabes que necesitas claridad.</p>
                <p>Sabes que necesitas volver a ti.</p>
                <p>Pero nunca encuentras el momento.</p>
                <p style="margin-top: 30px; font-weight: 600;">¿Y si este año es distinto?</p>
                <p style="font-weight: 600;">¿Y si, en lugar de seguir posponiéndote, te eliges a ti por fin?</p>
            </div>
        </section>

        <!-- BLOQUE 3: VISIÓN -->
        <section>
            <h2>Imagina tu Transformación</h2>
            <div class="vision-grid">
                <div class="vision-item">
                    <p>🧘‍♀️ Practicar yoga al amanecer frente a las dunas</p>
                </div>
                <div class="vision-item">
                    <p>💫 Sentir tu cuerpo vivo y tu mente en calma</p>
                </div>
                <div class="vision-item">
                    <p>⭐ Dormir bajo millones de estrellas en el Sahara</p>
                </div>
                <div class="vision-item">
                    <p>👯‍♀️ Conectar con mujeres como tú</p>
                </div>
                <div class="vision-item">
                    <p>🤝 Ser acompañada desde el primer minuto</p>
                </div>
                <div class="vision-item">
                    <p>✨ Volver con claridad, propósito y ligereza</p>
                </div>
            </div>
            <div style="text-align: center; margin-top: 30px; padding: 25px; background: white; border-radius: 8px;">
                <p style="font-size: 18px; color: #a67c52; font-weight: 600;">Esto no es turismo.</p>
                <p style="font-size: 18px; color: #a67c52; font-weight: 600;">Esto es transformación real.</p>
            </div>
        </section>

        <!-- BLOQUE 4: PARA QUIÉN ES -->
        <section>
            <h2>¿Es Para Ti?</h2>
            <div style="margin: 30px 0;">
                <h3 style="color: #a67c52; margin-bottom: 20px;">✔ Perfecto si eres una mujer que:</h3>
                <div class="target-list">
                    <div class="target-item">Busca reconexión interior</div>
                    <div class="target-item">Desea claridad mental</div>
                    <div class="target-item">Anhela una tribu auténtica</div>
                    <div class="target-item">Tiene miedo de viajar sola</div>
                    <div class="target-item">Necesita un espacio seguro y acompañado</div>
                    <div class="target-item">Está cansada de sostener a todos menos a sí misma</div>
                </div>
            </div>
            <div style="margin: 30px 0;">
                <h3 style="color: #999; margin-bottom: 20px;">❌ No es para ti si:</h3>
                <div class="target-list">
                    <div class="target-item">Buscas turismo masivo</div>
                    <div class="target-item">No deseas abrirte emocionalmente</div>
                    <div class="target-item">Quieres grupos grandes</div>
                    <div class="target-item">No buscas transformación real</div>
                </div>
            </div>
        </section>

        <!-- BLOQUE 5: OBJECCIONES -->
        <section>
            <h2>Lo Que Más Miedo da</h2>
            <div class="objection-item">
                <strong>"Me da miedo ir sola."</strong>
                <p>Perfecto. La mayoría vienen solas. Por eso existe este retiro: para que no te sientas sola ni un segundo.</p>
            </div>
            <div class="objection-item">
                <strong>"¿Y si no encajo?"</strong>
                <p>El grupo es íntimo y cuidadosamente seleccionado. Todas vienen por lo mismo: reconectar, sanar, abrirse. Aquí perteneces desde el primer día.</p>
            </div>
            <div class="objection-item">
                <strong>"¿Y si no es el momento para invertir en mí?"</strong>
                <p>Cuando vuelves con claridad y paz interna, todo en tu vida mejora. Este viaje NO es un gasto, es un reseteo vital.</p>
            </div>
        </section>

        <!-- BLOQUE 6: LO ÚNICO -->
        <section>
            <h2>Lo Que Hace Esto Único</h2>
            <div class="unique-feature">
                <div class="feature-number">⭐ 1. Mi acompañamiento (Rosa)</div>
                <p>Antes, durante y después. Es un retiro guiado con presencia real y emocional.</p>
            </div>
            <div class="unique-feature">
                <div class="feature-number">⭐ 2. Grupo íntimo (12 mujeres)</div>
                <p>Conexión profunda, segura y auténtica. Aquí nadie se queda atrás.</p>
            </div>
            <div class="unique-feature">
                <div class="feature-number">⭐ 3. Yoga para sanar</div>
                <p>Sesiones para desbloquear, soltar y reconectar con tu cuerpo y mente de verdad.</p>
            </div>
            <div class="unique-feature">
                <div class="feature-number">⭐ 4. Experiencias bereberes auténticas</div>
                <p>Talleres de cocina, taller de alfombras, música, desierto, familias nómadas. No es "Marruecos para turistas".</p>
            </div>
            <div class="unique-feature">
                <div class="feature-number">⭐ 5. Grupos de WhatsApp: antes y después</div>
                <p>Desde que reservas, ya tienes tribu. Después del viaje, sigues acompañada e integrada.</p>
            </div>
        </section>

        <!-- BLOQUE 7: ITINERARIO -->
        <section>
            <h2>Tu Itinerario Transformador</h2>
            <div class="itinerary">
                <div class="day-card">
                    <h4>DÍA 1 — El Despertar</h4>
                    <p>Llegada · Yoga suave · Intenciones · Tribu</p>
                </div>
                <div class="day-card">
                    <h4>DÍA 2 — Cruce del Atlas</h4>
                    <p>Montañas · Yoga energizante · Valle de Dades</p>
                </div>
                <div class="day-card">
                    <h4>DÍA 3 — Puertas del Sahara</h4>
                    <p>Gargantas de Todra · Yoga frente a dunas</p>
                </div>
                <div class="day-card">
                    <h4>DÍA 4 — El Renacimiento</h4>
                    <p>Amanecer en duna · Té con nómadas · Música gnawa · Yoga bajo estrellas</p>
                </div>
                <div class="day-card">
                    <h4>DÍA 5 — Integración</h4>
                    <p>Meditación · Valle del Draa · Yoga restaurativo</p>
                </div>
                <div class="day-card">
                    <h4>DÍA 6 — Regreso a la Tierra</h4>
                    <p>Yoga al amanecer · Círculo final · Marrakech</p>
                </div>
                <div class="day-card">
                    <h4>DÍA 7 — Nuevo Comienzo</h4>
                    <p>Jardines Majorelle · Souks · Almuerzo final</p>
                </div>
            </div>
        </section>

        <!-- BLOQUE 8: QUÉ INCLUYE -->
        <section>
            <h2>Lo Que Incluye (Valor Acumulado)</h2>
            <div class="includes-list">
                <div class="include-item">Alojamiento premium - Riad boutique + campamento bereber de lujo</div>
                <div class="include-item">Media pensión - Desayunos y cenas (en Marrakech solo desayuno)</div>
                <div class="include-item">12 sesiones de yoga y meditación - En terrazas, montañas, dunas y bajo estrellas</div>
                <div class="include-item">Talleres auténticos - Cocina bereber · Alfombras · Música gnawa</div>
                <div class="include-item">Transporte privado 4x4 - Conductor + guía en español</div>
                <div class="include-item">Actividades especiales - Dromedarios · Ait Benhaddou · Gargantas · Jardines y palmerales</div>
                <div class="include-item">Acompañamiento emocional (Rosa)</div>
                <div class="include-item">Grupo WhatsApp previo + Grupo post-viaje</div>
            </div>
            <h3 style="color: #a67c52; margin-top: 30px; margin-bottom: 15px;">Lo Que NO Incluye</h3>
            <div class="includes-list">
                <div class="not-include-item">Vuelos</div>
                <div class="not-include-item">Almuerzos</div>
                <div class="not-include-item">Seguro de viaje</div>
                <div class="not-include-item">Compras personales</div>
            </div>
        </section>

        <!-- BLOQUE 10: PRECIO -->
        <section>
            <h2>Inversión en Tu Transformación</h2>
            <div class="pricing-section">
                <div class="price-box">
                    <div class="price-label">🎁 EARLY BIRD (Solo 6 primeras plazas)</div>
                    <div class="price">890 €</div>
                </div>
                <div class="price-box">
                    <div class="price-label">Precio Regular</div>
                    <div class="price">1.020 €</div>
                </div>
                <div style="margin-top: 30px;">
                    <h3 style="color: white; margin-bottom: 20px;">Métodos de Pago</h3>
                    <p style="font-size: 16px;">💠 Reserva con 100 €</p>
                    <p style="font-size: 16px;">💠 Segundo pago 30 días antes</p>
                    <p style="font-size: 16px;">💠 Resto en destino</p>
                </div>
                <p style="margin-top: 30px; font-size: 18px; font-weight: 600;">127 €/día por una experiencia que cambia tu vida entera.</p>
            </div>
        </section>

        <!-- BLOQUE 11: TESTIMONIAL -->
        <section>
            <h2>Lo Que Dicen las Participantes</h2>
            <div class="testimonial">
                <p>"No sabía si ir sola. Era mi mayor miedo. A los 5 minutos en el grupo de WhatsApp ya estaba llorando de alivio. Este viaje me devolvió a mí misma."</p>
                <div class="author">— Participante del último retiro</div>
            </div>
        </section>

        <!-- BLOQUE 12: QUIÉN SOY ROSA -->
        <section>
            <h2>Quién Soy: Rosa</h2>
            <div class="about-rosa">
                <p>Durante años viví en piloto automático. Trabajando, cumpliendo, funcionando… Pero por dentro me sentía vacía.</p>
                <p>Hasta que un viaje a Marruecos me despertó. El desierto me enseñó silencio. La montaña me enseñó paciencia. El viaje me devolvió la vida.</p>
                <p>Hoy acompaño a mujeres a vivir lo mismo: a respirar de verdad, a volver a sentir, a recordar quiénes son.</p>
                <p style="font-weight: 600;">No te llevo al Marruecos turístico. Te llevo al Marruecos auténtico, humano, vibrante, al Marruecos que abraza y te sostiene. Y yo camino contigo cada paso.</p>
            </div>
        </section>
    </div>

    <!-- BLOQUE 13: CTA FINAL -->
    <section class="cta-section">
        <h2>¿Ready para tu transformación?</h2>
        <div class="cta-buttons">
            <button class="cta-btn-secondary" onclick="scrollToForm()">🔵 QUIERO MÁS INFORMACIÓN</button>
            <button class="cta-btn-secondary" onclick="openWhatsApp()">💬 HABLAR POR WHATSAPP</button>
            <button class="cta-btn-secondary" onclick="scrollToForm()">📝 RESERVAR MI LUGAR</button>
        </div>
    </section>

    <!-- BLOQUE 14: FORMULARIO -->
    <div class="container">
        <div class="form-section" id="contactForm">
            <h2 style="text-align: center; color: #a67c52; margin-bottom: 30px;">Cuéntame Más</h2>
            <form onsubmit="handleSubmit(event)">
                <div class="form-group">
                    <label for="name">Nombre</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="whatsapp">WhatsApp</label>
                    <input type="tel" id="whatsapp" name="whatsapp" required>
                </div>
                <div class="form-group">
                    <label for="message">¿Qué te trae aquí?</label>
                    <textarea id="message" name="message" rows="4" required></textarea>
                </div>
                <button type="submit" class="submit-btn">Enviar Mi Solicitud</button>
                <p style="text-align: center; margin-top: 15px; color: #999; font-size: 14px;">Te contactaré en menos de 24h por WhatsApp.</p>
            </form>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Retiro Alma Nómada. Todos los derechos reservados. | Rosa | Yoga & Transformación</p>
    </footer>

    <script>
        function scrollToForm() {
            document.getElementById('contactForm').scrollIntoView({
