# Komut Satırından Mesaj Yayınlama

Aşağıdaki komutu çalıştırarak rabbitmadmin uygulamasını kullanarak mesaj yayınlayın;

`rabbitmqadmin -u enterprisecoding -p enterprisecoding publish --vhost=default exchange=fanoutExchange routing_key="" payload="Enterprisecoding rabbitmq eğitimi ikinci örnek fanout mesajı"`{{execute}}

Önceki adımda tariflendiği şekilde mesajın kuyruklara teslim edildiğini teyit edin. Mesajları getirirken **Messages** değerini **2** olarak tanımlayın.