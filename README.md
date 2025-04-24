# 🎵 Análise de Métricas Spotify – Taylor Swift

Este repositório contém uma análise exploratória das métricas de áudio e de popularidade das músicas e álbuns de Taylor Swift no Spotify. O objetivo é entender padrões de engajamento, características sonoras e estratégias de lançamento ao longo da carreira da artista.

---

## 📁 Estrutura do Projeto

```
.
├── data/                           # Dados brutos (CSV) baixados do Kaggle
├── notebooks/                      # Jupyter Notebooks com a análise exploratória
│   └── analise_spotify_ts.ipynb
├── images/                        # Gráficos gerados (PNG)
│   ├── popularidade_por_tipo_album.png
│   ├── media_caracteristicas_album.png
│   ├── heatmap_caracteristicas_album.png
│   └── ...  
├── requirements.txt                # Dependências do Python
└── README.md                       # Este arquivo
```

--- 

## 📥 Fontes de Dados

- **Taylor Swift Spotify Dataset** – Jarred Priester, [Kaggle](https://www.kaggle.com/datasets/jarredpriester/taylor-swift-spotify-dataset) 


---

## 🚀 Como Executar

1. **Clone o repositório**  
   ```bash
   git clone https://github.com/alinepax/analise_spotify_taylorswift.git
   cd spotify-ts-analysis
   ```

2. **Instale as dependências**  
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute a análise**  
   - Abra o notebook principal:  
     ```bash
     jupyter notebook notebooks/analise_spotify_ts.ipynb
     ```
   - Ou rode o script completo de visualizações:  
     ```bash
     python scripts/plot_visualizations.py
     ```

---

## 📊 Principais Insights

1. **Eras Pop Energéticas**  
   - *1989*, *reputation*, *Lover* e *Midnights* lideram danceability, energy e valence, com acousticness baixa.  
2. **Projetos Introspectivos**  
   - *folklore* e *evermore* (incluindo edições deluxe/Long Pond) apresentam acousticness alta e métricas de energia/valence mais baixas.  
3. **Regravações & Deluxe**  
   - *Taylor’s Version* de *Fearless* e *Red* renovam o catálogo, mantendo popularidade e buzz em alta.  
4. **Consistência de Popularidade**  
   - Popularidade média acima de 50 em quase todo o catálogo, com picos em lançamentos estratégicos.

---

## 🛠️ Tecnologias e Ferramentas

- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  
- Spotify Web API

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 🤝 Contribuição

Contribuições são bem-vindas!  
1. Fork este repositório  
2. Crie uma branch com sua feature: `git checkout -b feature/nome-feature`  
3. Commit suas mudanças: `git commit -m 'Adiciona nova análise'`  
4. Push para a branch: `git push origin feature/nome-feature`  
5. Abra um Pull Request

---

## 👩‍💻 Sobre a Autora

Desenvolvido por **[Aline Paz](https://github.com/alinepax)**  
📫 Me encontre no [LinkedIn](https://www.linkedin.com/in/alinedapaz/)  
📧 Meu email: aline.santospaz@gmail.com  
🎯 Este projeto faz parte do meu portfólio como profissional em transição para a área de Dados e Tecnologia.

---

⭐ Se você gostou, deixe uma estrela no repositório!
