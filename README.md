# PROYECT-3
CV 
[[CV]][(https://claude.ai/public/artifacts/862dbb3f-ab6c-432a-8c09-3857c1b33bb6CV)](<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Milena González</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 40px 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 850px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
        }
        
        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 50px 40px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            font-weight: 600;
        }
        
        .header .subtitle {
            font-size: 1.3em;
            opacity: 0.95;
            margin-bottom: 5px;
        }
        
        .header .field {
            font-size: 1.1em;
            opacity: 0.9;
            font-weight: 300;
        }
        
        .content {
            padding: 40px;
        }
        
        .section {
            margin-bottom: 35px;
        }
        
        .section-title {
            color: #667eea;
            font-size: 1.5em;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 3px solid #667eea;
            font-weight: 600;
        }
        
        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .info-item {
            display: flex;
            align-items: center;
            padding: 15px;
            background: #f8f9ff;
            border-radius: 8px;
            transition: transform 0.2s;
        }
        
        .info-item:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.2);
        }
        
        .info-icon {
            width: 40px;
            height: 40px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            flex-shrink: 0;
        }
        
        .info-icon svg {
            width: 20px;
            height: 20px;
            fill: white;
        }
        
        .info-text {
            flex: 1;
        }
        
        .info-label {
            font-size: 0.85em;
            color: #666;
            margin-bottom: 3px;
        }
        
        .info-value {
            font-size: 1em;
            color: #333;
            font-weight: 500;
        }
        
        .section-content {
            padding: 20px;
            background: #f8f9ff;
            border-radius: 8px;
            line-height: 1.8;
            color: #555;
        }
        
        .section-content p {
            margin-bottom: 10px;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        
        .skill-item {
            padding: 12px 20px;
            background: #f8f9ff;
            border-radius: 8px;
            border-left: 4px solid #667eea;
            font-weight: 500;
            color: #333;
        }
        
        @media print {
            body {
                background: white;
                padding: 0;
            }
            .container {
                box-shadow: none;
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Milena González</h1>
            <div class="subtitle">Estudiante de Marketing</div>
            <div class="field">Especialización en Marketing</div>
        </div>
        
        <div class="content">
            <div class="section">
                <h2 class="section-title">Información de Contacto</h2>
                <div class="info-grid">
                    <div class="info-item">
                        <div class="info-icon">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                <path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
                            </svg>
                        </div>
                        <div class="info-text">
                            <div class="info-label">Email</div>
                            <div class="info-value">Milenagonzalez244@gmail.com</div>
                        </div>
                    </div>
                    
                    <div class="info-item">
                        <div class="info-icon">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                <path d="M19 3h-1V1h-2v2H8V1H6v2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm0 16H5V8h14v11z"/>
                            </svg>
                        </div>
                        <div class="info-text">
                            <div class="info-label">Fecha de Nacimiento</div>
                            <div class="info-value">24 de febrero de 2004</div>
                        </div>
                    </div>
                    
                    <div class="info-item">
                        <div class="info-icon">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm0-12.5c-2.49 0-4.5 2.01-4.5 4.5s2.01 4.5 4.5 4.5 4.5-2.01 4.5-4.5-2.01-4.5-4.5-4.5z"/>
                            </svg>
                        </div>
                        <div class="info-text">
                            <div class="info-label">Edad</div>
                            <div class="info-value">20 años</div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">Perfil Profesional</h2>
                <div class="section-content">
                    <p>Estudiante de Marketing joven y entusiasta, con pasión por las estrategias de comunicación y el análisis del comportamiento del consumidor. Comprometida con el aprendizaje continuo y el desarrollo de habilidades en el ámbito del marketing digital y tradicional.</p>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">Formación Académica</h2>
                <div class="section-content">
                    <p><strong>Estudiante de Marketing</strong></p>
                    <p>Actualmente cursando estudios en Marketing</p>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">Habilidades</h2>
                <div class="skills-grid">
                    <div class="skill-item">Marketing Digital</div>
                    <div class="skill-item">Redes Sociales</div>
                    <div class="skill-item">Análisis de Mercado</div>
                    <div class="skill-item">Comunicación</div>
                    <div class="skill-item">Trabajo en Equipo</div>
                    <div class="skill-item">Creatividad</div>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">Objetivos</h2>
                <div class="section-content">
                    <p>Aplicar mis conocimientos de marketing en un entorno profesional, desarrollar experiencia práctica en estrategias de marketing y contribuir al crecimiento de una organización mediante ideas innovadoras y trabajo dedicado.</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>]]
