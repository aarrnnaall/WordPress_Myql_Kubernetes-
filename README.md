Aplicar los Yamls->
-kubectl apply -k ./

Te devuelve->
secret/secretgenerator-kfthgh9h4d unchanged
service/wordpress-mysql unchanged
service/wordpress unchanged
deployment.apps/wordpress-mysql unchanged
deployment.apps/wordpress unchanged
persistentvolumeclaim/wordpress-mysql-persistentvolume unchanged
persistentvolumeclaim/wordpress-persistentvolume unchanged

Para deternerlos->
-kubectl delete -k ./
