<html lang="pt-BR">
<body>
  <header>
    <h1>Guia Completo da Linguagem Lua no Roblox</h1>
    <p>Aprenda todos os comandos e conceitos essenciais de programação em Roblox Studio!</p>
  </header>

  <main>
    <section>
      <h2>🌟 Introdução</h2>
      <p>Lua é a linguagem usada no Roblox para criar scripts, controlar o comportamento dos jogos e tornar tudo interativo. É simples, leve e muito poderosa.</p>
    </section>

    <section>
      <h2>🧱 Estrutura Básica</h2>
      <p>Um script em Lua é executado linha por linha. Aqui estão alguns comandos básicos:</p>
      <pre><code>print("Olá, Roblox!")
local nome = "Jogador"
local idade = 13
print(nome .. " tem " .. idade .. " anos!")</code></pre>
      <ul>
        <li><strong>print()</strong>: Exibe mensagens no console.</li>
        <li><strong>local</strong>: Cria variáveis locais (válidas apenas dentro do bloco de código).</li>
        <li><strong>..</strong>: Concatena textos.</li>
      </ul>
    </section>

    <section>
      <h2>⚙️ Estruturas de Controle</h2>
      <p>Esses comandos permitem criar decisões e repetições:</p>
      <pre><code>-- Condicional
local vida = 80
if vida > 50 then
  print("Você está saudável!")
elseif vida > 0 then
  print("Cuidado!")
else
  print("Game Over!")
end

-- Loop for
for i = 1, 5 do
  print("Contagem: " .. i)
end

-- Loop while
local energia = 3
while energia > 0 do
  print("Energia restante: " .. energia)
  energia = energia - 1
end</code></pre>
    </section>

    <section>
      <h2>🔁 Funções</h2>
      <p>Funções permitem reutilizar blocos de código.</p>
      <pre><code>function saudar(nome)
  print("Olá, " .. nome .. "!")
end

saudar("Guilherme")</code></pre>
      <p>No Roblox, funções são essenciais para eventos e interações.</p>
    </section>

    <section>
      <h2>🎮 Eventos no Roblox</h2>
      <p>Os eventos permitem reagir a ações no jogo. Exemplo:</p>
      <pre><code>local botao = script.Parent
botao.MouseButton1Click:Connect(function()
  print("Botão clicado!")
end)</code></pre>
      <ul>
        <li><strong>:Connect(function)</strong>: liga uma função a um evento.</li>
        <li><strong>MouseButton1Click</strong>: evento de clique do mouse.</li>
      </ul>
    </section>

    <section>
      <h2>🧩 Tabelas</h2>
      <p>As tabelas são usadas para armazenar listas e dicionários de dados.</p>
      <pre><code>local frutas = {"maçã", "banana", "uva"}
for i, fruta in ipairs(frutas) do
  print(fruta)
end

local jogador = {nome = "Gui", nivel = 5, vida = 100}
print(jogador.nome)</code></pre>
    </section>

    <section>
      <h2>💥 Manipulando Objetos no Roblox</h2>
      <p>Comandos usados para interagir com objetos no jogo:</p>
      <pre><code>local parte = Instance.new("Part")
parte.Parent = game.Workspace
parte.BrickColor = BrickColor.new("Bright blue")
parte.Position = Vector3.new(0, 10, 0)</code></pre>
      <ul>
        <li><strong>Instance.new()</strong>: cria um novo objeto.</li>
        <li><strong>Parent</strong>: define onde o objeto será colocado.</li>
        <li><strong>BrickColor</strong>: muda a cor.</li>
        <li><strong>Vector3.new()</strong>: define posições 3D.</li>
      </ul>
    </section>

    <section>
      <h2>⚡ Funções Úteis do Roblox</h2>
      <ul>
        <li><strong>wait(segundos)</strong>: pausa o script por um tempo.</li>
        <li><strong>game.Workspace</strong>: representa o mundo 3D.</li>
        <li><strong>script.Parent</strong>: acessa o objeto pai do script.</li>
        <li><strong>print()</strong>: mostra mensagens no console.</li>
        <li><strong>math.random(a,b)</strong>: gera números aleatórios.</li>
      </ul>
    </section>

    <section>
      <h2>🚀 Exemplo Completo</h2>
      <p>Veja um exemplo de script simples de spawn de blocos coloridos:</p>
      <pre><code>for i = 1, 10 do
  local bloco = Instance.new("Part")
  bloco.Size = Vector3.new(2,2,2)
  bloco.Position = Vector3.new(math.random(-50,50), 10, math.random(-50,50))
  bloco.BrickColor = BrickColor.Random()
  bloco.Parent = game.Workspace
  wait(0.2)
end</code></pre>
    </section>

    <section>
      <h2>🧠 Conclusão</h2>
      <p>Dominar Lua no Roblox abre portas para criar jogos incríveis. Comece praticando com scripts simples e avance para sistemas complexos, como lojas, NPCs e animações.</p>
    </section>
  </main>

  <footer>
    © 2025 Mundo Roblox — Tutorial completo de programação Lua
  </footer>
</body>
</html># SiteLinguagemLua.github.com
