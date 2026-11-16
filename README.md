# 📒 Caderninho Inteligente da Maria

Assistente conversacional inspirado no WhatsApp, desenvolvido para simplificar o controle de vendas, cobranças (fiado) e rastreios de pequenos lojistas sem afinidade com tecnologia.

🔗 **Acesse a aplicação funcionando:** [caderninho-maria.vercel.app](https://caderninho-maria.vercel.app)

---

## 💡 O Problema
Em pequenos comércios, o registro diário de vendas muitas vezes é feito na correria em planilhas manuais, gerando inconsistências como:
- Datas misturadas ou relativas (*"ontem"*, *"hoje"*, *"segunda"*);
- Dados trocados de coluna (como códigos de rastreio digitados no campo do cliente);
- Compras de estoque e devoluções somadas junto com o faturamento;
- Vendas a prazo (**fiado**) perdidas no meio das anotações.

## 🎯 A Solução
Em vez de um sistema complexo cheio de menus e formulários rígidos, o **Caderninho Inteligente da Maria** adapta a tecnologia à rotina real da usuária:

- **Registro por linguagem natural:** Basta digitar uma frase comum (ex: *"Vendi um colar dourado pra Ana por 89 no pix, vai pelos correios"*) e o sistema extrai produto, cliente, valor, pagamento e entrega automaticamente.
- **Confirmação humana antes de salvar:** Cartão de revisão simples (*"Sim, salvar"* ou *"Corrigir"*) para evitar erros de interpretação.
- **Resgate da base histórica:** Tratamento e padronização de uma base real com 72 registros sem perda de informação[cite: 2].
- **Controle visual de fiados:** Destaque automático em **vermelho** para vendas em aberto, com baixa rápida em 1 clique (*"Recebi"*).
- **Acessibilidade:** Botões visíveis para aumentar ou diminuir o tamanho da fonte (**A- / A+**).
- **Exportação Excel (`.xlsx`):** Download instantâneo da planilha organizada, formatada e dividida em abas.

## 🛠️ Tecnologias Utilizadas
- **Inteligência Artificial (Gemini):** Diagnóstico dos dados, regras de saneamento e apoio no desenvolvimento.
- **Python (Pandas & OpenPyXL):** Análise exploratória e limpeza da base histórica.
- **HTML5, Tailwind CSS & JavaScript:** Interface web responsiva, leve e acessível.
- **ExcelJS:** Geração dinâmica de planilhas `.xlsx` estilizadas diretamente no navegador.
- **GitHub & Vercel:** Versionamento e hospedagem contínua.

---

👩‍💻 **Desenvolvido por:** [Isabelli Cristina Armanelli](https://github.com/isaarmanelli0817-byte)
