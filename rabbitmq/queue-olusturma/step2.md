# Komut Satırından Queue Oluşturma

Aşağıdaki komutu çalıştırarak rabbitmqadmin uygulamasını yerele indirin;

`wget http://localhost:15672/cli/rabbitmqadmin -O /usr/local/bin/rabbitmqadmin`{{execute}}

İndirdiğiniz dosyayı çalıştırılabilir olarak işaretleyin;

`chmod +x /usr/local/bin/rabbitmqadmin`{{execute}}

Aşağıdaki komutla **Direct** türündeki **lab.queue.iki**'i tanımlayın;

`rabbitmqadmin -u enterprisecoding -p enterprisecoding declare queue --vhost=default name=lab.queue.iki durable=true`{{execute}}

Yönetim arayüzüne giderek queue'un oluşturulduğunu teyit edin.
