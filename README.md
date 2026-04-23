# festival

# Começei por analisar as views: Concerto e Palco
- Concerto: preenchi a variável com Concerto.objects.all() para obter todos os concertos
- Palco: tive que criar a view
- fiz o import de todos os modelos

# dias.html
- Tive que adicionar o template dias.html com base no template base (layout.html)
- Adicionei o respetivo caminho no urls.py para aceder à página dos dias

# Detalhe 
- Para obter o detalhe do concerto,utilizei um link na página palcos.html
bash
  href="{% url 'concerto' concerto.id %}">...



