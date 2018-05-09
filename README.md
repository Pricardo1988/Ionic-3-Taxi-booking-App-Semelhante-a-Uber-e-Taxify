# Ionic-3-Taxi-booking-App-Semelhante-a-Uber-e-Taxify
Este é um aplicativo completo de reserva de viagens construído com ionic3, Ele usa o plug-in do Google Maps Cordova, firebase como banco de dados em tempo real e onesignal como provedor de notificação.


# Características
Google Maps SDK Cordova
Firebase Realtime DB
Onesignal (Google Cloud Messaging)
Paystack
Como funciona
Inicie o aplicativo
Para este projeto, criei dois aplicativos diferentes. O aplicativo cliente e o aplicativo Driver. Depois de criar uma conta, adicionar um número de telefone, seu local é detectado automaticamente por meio da geolocalização do Google Maps, mas você pode apontar o marcador para outro local para escolher outro local.

# Solicitar um táxi
Quando um usuário registra um passeio, então os detalhes do usuário são enviados para o banco de dados com o ID de notificação do primeiro driver disponível, depois de 60 segundos e sem resposta, em seguida, é deslocado para outro driver.

# Seja aceito por um motorista
Depois de obter um driver, em seguida, seu telefone vibra e as credenciais do driver aparece na tela, bem como a distância entre você e seu driver são exibidas também.

# Chegar ao seu destino e pagar
Na conclusão do passeio, seu pagamento é mostrado para você, então você pode verificar e avaliar sua viagem e, em seguida, você está pronto para outra reserva.

Este projeto é um clone completo do Uber, que é um aplicativo de reserva de táxi. Esta venda vem com código fonte de 100% para o aplicativo do usuário, Driver App.
Recursos neste aplicativo
Intro tela inicial para dar uma aparência atraente para o aplicativo. Integração de API do Google para preenchimento automático. Plotagem de locais para o google map com distância e cálculo de minutos entre rotas. Um passo e processo de reserva fácil. Integração com o gateway de pagamento de faixas. Opção para definir tipos de cabina com taxas do Firebase de back-end. Animação elegante entre visualizações com menu de slides estilo Facebook. Exibir todas as reservas com rolagem para carregar e limpar a interface do usuário. Ativar atualização automática quando o driver aceitar o trabalho na chegada do motorista, jornada iniciada, jornada concluída / descartada, etc. Suporte Mensagens push para todo o status também. Driver de rastreamento ao vivo que é atribuído para a sua reserva. Opção para cancelar o trabalho até que o driver não seja atribuído. Ecrã do cartão de taxas O usuário pode avaliar o driver após a conclusão do passeio, também o motorista pode avaliar o usuário também.

# Recurso App Driver
Formulário de registro de 3 etapas com toda a captura de campo e validação necessárias para tornar o aplicativo pronto para ser ativado. Menu deslizante de estilo do Facebook. Opção para definir status disponível e indisponível ... Suporte Firebase Tempo real para rastreamento de driver. Suporte FCM notificação Interface quando a nova reserva é chegada e o telefone começará a apitar. Node.js Atribuição automática de Driver para Jobs com base na disponibilidade do Driver avaibality, tipo de carro e driver disponível mais próximo usando as Consultas GEO Robust Spatial. Suporte Envie mensagens para o driver se o aplicativo estiver em segundo plano. .. Calcular tarifas com base em Milhas + Minutos exigem a viagem. .

# Recursos no administrador da Web:
Limpo e fácil de entender Painel que exibe todas as estatísticas relevantes.

Visualize a atividade em tempo real de motorista e passageiro no mapa. Exibir tudo Driver .. Exibir tudo o que o usuário .. Exibir driver sinalizado e Opção para bloqueá-los .. Exibir usuário sinalizado e opção para bloquear usuários .. Opção para visualizar todos os usuários .. Definir preços para tipos de carro .. Definir moedas .. E muito Mais …
