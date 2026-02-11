## 🧠 3. Laboratório 3 – Prática 2 (Language Studio)

Passos gerais:

1. No portal Azure: [https://portal.azure.com/#home](https://portal.azure.com/#home).  
2. Clique em **Criar um recurso**.  
3. Em **Categorias**, selecione **AI + Machine Learning**.  
4. Escolha o serviço **Language service**.  
5. Clique no botão azul **Criar**.  
6. Preencha:
   - **Resource group** (use o mesmo grupo ou crie outro, se preferir).
   - **Nome** do recurso de Language.
   - Em **Pricing tier**, selecione **Free F0**.
   - Confirme que está na opção sem cobrança (quando disponível).
7. Após a validação, clique em **Create** e aguarde a criação do recurso.  

Em seguida:

8. Acesse o **Language Studio**: [https://language.cognitive.azure.com/home](https://language.cognitive.azure.com/home).  
9. Selecione:
   - A sua **subscrição** (se não renomeou, provavelmente estará como “Subscrição”).  
   - O **resource group** que você criou.  
   - O **recurso de Language** configurado (nome definido na etapa anterior).  
10. Confirme o plano **Free F0** e conclua.  
11. No Language Studio, crie um novo recurso para **classificação de texto** (por exemplo, “Classify text”).  
12. Selecione o idioma do texto (ex.: português).  
13. Cole o texto que deseja analisar (por exemplo, texto transcrito do Speech Studio).  
14. Execute a análise: o serviço deve retornar:
    - Palavras-chave/frases-chave.
    - Classificação de sentimentos (positivo, negativo, neutro), dependendo do cenário escolhido.

No arquivo `04-language-studio.md`, registre:
- Texto analisado.  
- Tipo de análise escolhida (classificação, sentimento, palavras-chave).  
- Resultados obtidos.  
- Insights sobre possíveis usos (ex.: atendimento, análise de feedbacks, transcrição de reuniões etc.).  

---

