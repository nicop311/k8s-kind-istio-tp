# Manipulation avec Istio framework de service-mesh

## Etape 1

Lien pour installer votre environnement de TP :
https://github.com/nicop311/k8s-kind-istio-tp/blob/main/documentation/install-environment.md

Vous pour abandonnez l'installation de HELM ainsi que de Keycloak.


## Etape 2

Déployer une application exemple "Bookinfo"

* https://istio.io/latest/docs/examples/bookinfo/#deploying-the-application
* https://istio.io/latest/docs/tasks/traffic-management/ingress/ingress-control/#determining-the-ingress-ip-and-ports

## Etape 3

Exposer l'application Bookinfo en HTTPS avec TLS

* [suivez ce lien] https://betterprogramming.pub/kubernetes-services-over-https-with-istios-secure-gateways-210b2ce91b71
* https://istio.io/latest/docs/tasks/traffic-management/ingress/secure-ingress/


## Etape 4

Filtrage (en fonction de URL/FQDN) du traffic sortant (Egress)
https://istio.io/latest/docs/tasks/traffic-management/egress/egress-gateway/


## Etape 5

Perform mutual TLS origination with an egress gateway

* https://istio.io/latest/docs/tasks/traffic-management/egress/egress-gateway-tls-origination/

Plus précisément : 
https://istio.io/latest/docs/tasks/traffic-management/egress/egress-gateway-tls-origination/#perform-mutual-tls-origination-with-an-egress-gateway


## Etape Bonus

Manipulation de JWT (JSON Web Token) avec Keycloak.
https://labs.consol.de/development/2020/05/07/istio-and-keycloak.html