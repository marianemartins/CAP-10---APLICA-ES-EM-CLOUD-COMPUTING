# CAP-10---APLICA-ES-EM-CLOUD-COMPUTING
Utilizei a API da mapquest para gerar um staticmap no projeto de hospedagem.
Com ela eu consegui substituir o antigo mapa da localização do hotel utilizando coordenadas

Atenção, a API foi aplicada no hotel: 
Blue Tree Premium;
![image](https://user-images.githubusercontent.com/79736834/132109436-19395c42-dc77-4500-bd89-28ab6d67b717.png)

Ao clicar no hotel, a API carrega a imagem do mapa onde as coordenadas injetadas -23.55987743398744, -46.656155797339885 no código HTML são exibidas. Antes dessa implementação era necessário subir as imagens de cada hotel, agora podemos apenas adicionar as coordenadas e a imagem será gerada automaticamente. 

A figura abaixo mostra o código utilizado para a implementação, utilizando a chave + as coordenadas:

![image](https://user-images.githubusercontent.com/79736834/132109399-39bf1edf-bac4-4f1e-8f17-3b16a17ec56e.png)

E este é o resultado gerado no front:

![image](https://user-images.githubusercontent.com/79736834/132109343-80033088-044d-47f9-8ac6-5fa3151b673f.png)




