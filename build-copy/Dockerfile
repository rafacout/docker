FROM nginx:latest
LABEL maintainer 'Rafael Coutinho'

#cria um marquivo com o conteudo abaixo
RUN echo '<h1>Sem conteudo</h1>' > /usr/share/nginx/html/conteudo.html

#Copia o arquivo pra dentro da imagem no caminho do nginx
COPY *.html /usr/share/nginx/html/