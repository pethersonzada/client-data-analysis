## Análise de Cancelamentos de Clientes

Este projeto visa identificar os principais motivos de cancelamento de clientes em uma empresa com mais de 800 mil clientes. A partir dessa análise, são propostas ações para reduzir a taxa de cancelamentos.

Bibliotecas usadas:

    pandas: Manipulação de dados.
    numpy: Suporte para operações matemáticas.
    openpyxl: Leitura de arquivos Excel.
    nbformat e ipykernel: Suporte para notebooks Jupyter.
    plotly: Criação de gráficos interativos.

### Como usar:

Instale as dependências necessárias:

    pip install pandas numpy openpyxl nbformat ipykernel plotly

Certifique-se de que o arquivo tabela_cancelamentos.csv está no diretório correto.
Execute o script para analisar as causas dos cancelamentos e gerar gráficos.

### Etapas do Processo:

Limpeza dos dados:
    
        Colunas irrelevantes e valores nulos/duplicados são removidos.
    
Análise de cancelamentos:

        A quantidade e a porcentagem de clientes que cancelaram são calculadas.
        
 Visualização de dados:
    
        Gráficos interativos são gerados para cada coluna, destacando a relação entre variáveis como duracao_contrato, ligacoes_callcenter e dias_atraso com o cancelamento.

### Soluções propostas:
    
        Contrato mensal: Todos os clientes com contrato mensal cancelaram. Solução: oferecer descontos para planos anuais e trimestrais.
        Ligações ao call center: Clientes que ligaram mais de 4 vezes cancelaram. Solução: resolver problemas em no máximo 3 ligações.
        Atraso de pagamento: Clientes que atrasaram mais de 20 dias cancelaram. Solução: política para resolver atrasos em até 10 dias.

Impacto das ações:

        Após aplicar as soluções propostas, a taxa de cancelamento foi reduzida de 56,7% para 18,4%.

### Comentário!

Este código foi comentado por mim durante todo o processo de desenvolvimento. Caso algum erro seja encontrado, peço desculpas, pois os comentários refletem apenas minha linha de raciocínio, com o objetivo de tornar o código o mais didático possível.

## Aviso de Direitos Autorais

Este código foi desenvolvido por Miguel Petherson e está protegido por direitos autorais. Ele não possui uma licença aberta, o que significa que:  

- **Você não tem permissão para copiar, modificar ou redistribuir este código sem autorização prévia do autor.**
- Caso queira usar este código para qualquer finalidade, entre em contato por email - pethersonzada@gmail.com  

Por favor, respeite os direitos autorais e o trabalho investido neste projeto.  
Agradeço pela compreensão! 😊

