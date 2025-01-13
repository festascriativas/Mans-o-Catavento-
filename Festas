<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mansão Catavento</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <style>
        /* Estilos gerais */
        body {
            font-family: 'Comic Sans MS', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fce4ec;
        }
        header {
            background: linear-gradient(90deg, #ff8a80, #ff80ab);
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
        header h1 {
            font-size: 3rem;
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }
        header .logo {
            font-family: 'Comic Sans MS', sans-serif;
            font-size: 2.5rem;
            color: #fdd835; /* cor amarela */
            font-weight: bold;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
            margin-top: 1rem;
        }
        main {
            max-width: 900px;
            margin: 2rem auto;
            background: #ffffff;
            padding: 1.5rem;
            border-radius: 16px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #ff80ab;
            font-size: 1.8rem;
            margin-bottom: 1rem;
        }
        section {
            margin-bottom: 2rem;
        }
        label {
            display: block;
            margin: 0.8rem 0;
            font-size: 1rem;
            color: #424242;
        }
        input[type="checkbox"] {
            margin-right: 0.5rem;
        }
        input[type="text"], input[type="textarea"] {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 1rem;
        }
        button {
            display: block;
            margin: 1rem auto;
            background: linear-gradient(90deg, #ff4081, #ff80ab);
            color: white;
            border: none;
            padding: 0.8rem 2rem;
            border-radius: 8px;
            font-size: 1.2rem;
            cursor: pointer;
        }
        button:hover {
            background: linear-gradient(90deg, #d500f9, #ff80ab);
        }

        /* Responsividade */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            main {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Mansão Catavento</h1>
        <div class="logo">Festas Criativas</div> <!-- Logo estilizada -->
        <p>Selecione as opções para o seu evento</p>
    </header>
    <main>
        <form id="eventoForm">
            <!-- Nome do Cliente e Tema -->
            <section>
                <h2>Informações do Cliente</h2>
                <label for="nome">Nome do Cliente</label>
                <input type="text" id="nome" name="nome" placeholder="Digite seu nome" required>

                <label for="tema">Tema da Festa</label>
                <input type="text" id="tema" name="tema" placeholder="Digite o tema da festa" required>
            </section>

            <!-- Seções de seleção de itens -->
            <section>
                <h2>Entrada</h2>
                <label><input type="checkbox" name="entrada" value="Portal 6x4 - R$ 590,00"> Portal 6x4 - R$ 590,00</label>
                <label><input type="checkbox" name="entrada" value="Placa com Nome - R$ 190,00"> Placa com Nome - R$ 190,00</label>
                <label><input type="checkbox" name="entrada" value="Totem do Tema - R$ 150,00"> Totem do Tema - R$ 150,00</label>
            </section>

            <section>
                <h2>Recepção</h2>
                <label><input type="checkbox" name="recepcao" value="Armário para Lembrança - R$ 190,00"> Armário para Lembrança - R$ 190,00</label>
                <label><input type="checkbox" name="recepcao" value="Caixa Temática - R$ 90,00"> Caixa Temática - R$ 90,00</label>
                <label><input type="checkbox" name="recepcao" value="Carpete - R$ 100,00"> Carpete - R$ 100,00</label>
                <label><input type="checkbox" name="recepcao" value="Escultura Média - R$ 290,00"> Escultura Média - R$ 290,00</label>
                <label><input type="checkbox" name="recepcao" value="Foto da Criança"> Foto da Criança</label>
            </section>

            <section>
                <h2>Lateral Blindex</h2>
                <label><input type="checkbox" name="lateral" value="Cortina - R$ 290,00"> Cortina - R$ 290,00</label>
                <label><input type="checkbox" name="lateral" value="Carpete - R$ 150,00"> Carpete - R$ 150,00</label>
                <label><input type="checkbox" name="lateral" value="Tapete Impresso"> Tapete Impresso</label>
                <label><input type="checkbox" name="lateral" value="Esculturas a Definir"> Esculturas a Definir</label>
                <label><input type="checkbox" name="lateral" value="Painel Impresso"> Painel Impresso</label>
                <label><input type="checkbox" name="lateral" value="Forração Lateral"> Forração Lateral</label>
            </section>

            <section>
                <h2>Mesa do Parabéns</h2>
                <label><input type="checkbox" name="mesaParabens" value="Painel Reto - R$ 290,00"> Painel Reto - R$ 290,00</label>
                <label><input type="checkbox" name="mesaParabens" value="Forração Reto - R$ 290,00"> Forração Reto - R$ 290,00</label>
                <label><input type="checkbox" name="mesaParabens" value="Painel em U - R$ 590,00"> Painel em U - R$ 590,00</label>
                <label><input type="checkbox" name="mesaParabens" value="Forração em U - R$ 590,00"> Forração em U - R$ 590,00</label>
                <label><input type="checkbox" name="mesaParabens" value="Balão Orgânico"> Balão Orgânico</label>
                <label><input type="checkbox" name="mesaParabens" value="Balão a Gás"> Balão a Gás</label>
                <label><input type="checkbox" name="mesaParabens" value="Flores Naturais"> Flores Naturais</label>
                <label><input type="checkbox" name="mesaParabens" value="Flores Permanentes"> Flores Permanentes</label>
                <label><input type="checkbox" name="mesaParabens" value="Palco"> Palco</label>
                <label><input type="checkbox" name="mesaParabens" value="Idade Gigante"> Idade Gigante</label>
            </section>

            <section>
                <h2>Mobiliário para Composição dos Doces</h2>
                <label><input type="checkbox" name="mobiliarioDoces" value="9 Mobiliários Standard - R$ 810,00"> 9 Mobiliários Standard - R$ 810,00</label>
                <label><input type="checkbox" name="mobiliarioDoces" value="Mesa Cenográfica - R$ 1990,00"> Mesa Cenográfica - R$ 1990,00</label>
                <label><input type="checkbox" name="mobiliarioDoces" value="Bandejas - R$ 19,90 (Média 15 Doces por Bandeja)"> Bandejas - R$ 19,90 (Média 15 Doces por Bandeja)</label>
            </section>

            <section>
                <h2>Tapete Mesa do Bolo</h2>
                <label><input type="checkbox" name="tapeteBolo" value="Carpete - R$ 290,00"> Carpete - R$ 290,00</label>
                <label><input type="checkbox" name="tapeteBolo" value="Impressos - R$ 390,00"> Impressos - R$ 390,00</label>
            </section>

            <section>
                <h2>Personagens</h2>
                <label><input type="checkbox" name="personagens" value="Escultura Média - R$ 290,00 cada"> Escultura Média - R$ 290,00 cada</label>
                <label><input type="checkbox" name="personagens" value="Totem - R$ 150,00 cada"> Totem - R$ 150,00 cada</label>
            </section>

            <section>
                <h2>Doces Mesa do Parabéns</h2>
                <label><input type="checkbox" name="doces" value="Modelados"> Modelados</label>
                <label><input type="checkbox" name="doces" value="Papelaria"> Papelaria</label>
                <label><input type="checkbox" name="doces" value="Maquete de Luxo"> Maquete de Luxo</label>
                <label><input type="checkbox" name="doces" value="Maquete Padrão"> Maquete Padrão</label>
            </section>

            <section>
                <h2>Salão dos Convidados</h2>
                <label><input type="checkbox" name="salão" value="7 Avanços - R$ 990,00"> 7 Avanços - R$ 990,00</label>
                <label><input type="checkbox" name="salão" value="7 Cortinas - R$ 690,00"> 7 Cortinas - R$ 690,00</label>
                <label><input type="checkbox" name="salão" value="Painel em todo salão"> Painel em todo salão</label>
                <label><input type="checkbox" name="salão" value="Forração em todo salão"> Forração em todo salão</label>
            </section>

            <section>
                <h2>Mesa dos Convidados</h2>
                <label><input type="checkbox" name="mesaConvidados" value="Toalha da Casa"> Toalha da Casa</label>
                <label><input type="checkbox" name="mesaConvidados" value="Toalha Longa na Cor"> Toalha Longa na Cor</label>
                <label><input type="checkbox" name="mesaConvidados" value="Souplat Individual"> Souplat Individual</label>
                <label><input type="checkbox" name="mesaConvidados" value="Souplat Central"> Souplat Central</label>
                <label><input type="checkbox" name="mesaConvidados" value="Guardanapo"> Guardanapo</label>
                <label><input type="checkbox" name="mesaConvidados" value="Porta Guardanapo"> Porta Guardanapo</label>
                <label><input type="checkbox" name="mesaConvidados" value="Taça"> Taça</label>
                <label><input type="checkbox" name="mesaConvidados" value="Arranjo de Mesa"> Arranjo de Mesa</label>
                <label><input type="checkbox" name="mesaConvidados" value="Balão a Gás"> Balão a Gás</label>
                <label><input type="checkbox" name="mesaConvidados" value="Cardápio"> Cardápio</label>
            </section>

            <section>
                <h2>Outros</h2>
                <label><input type="checkbox" name="outros" value="Carregamento Ida"> Carregamento Ida</label>
                <label><input type="checkbox" name="outros" value="Carregamento Volta"> Carregamento Volta</label>
                <label><input type="checkbox" name="outros" value="Montagem"> Montagem</label>
                <label><input type="checkbox" name="outros" value="Desmontagem"> Desmontagem</label>
                <label><input type="checkbox" name="outros" value="Iluminação"> Iluminação</label>
                <label><input type="checkbox" name="outros" value="Sonorização"> Sonorização</label>
                <label><input type="checkbox" name="outros" value="Personagens"> Personagens</label>
                <label><input type="checkbox" name="outros" value="Animação"> Animação</label>
            </section>

            <button type="submit">Gerar PDF</button>
        </form>
    </main>

    <script>
        document.getElementById('eventoForm').addEventListener('submit', function(event) {
            event.preventDefault();

            const { jsPDF } = window.jspdf;
            const doc = new jsPDF();

            const formData = new FormData(this);
            let content = 'Mansão Catavento\n\n';

            formData.forEach((value, key) => {
                if (value) {
                    content += `${key}: ${value}\n`;
                }
            });

            doc.text(content, 10, 10);
            doc.save('formulario_evento.pdf');
        });
    </script>
</body>
</html>
