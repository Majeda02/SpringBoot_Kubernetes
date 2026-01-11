# Déploiement d’une application Spring Boot sur Kubernetes

## Objectifs pédagogiques
À la fin de ce lab, l’étudiant est capable de :
* Conteneuriser une application Spring Boot avec Docker.
* Créer les manifests Kubernetes de base : Deployment et Service.
* Déployer l’application sur un cluster Kubernetes local (par exemple Minikube).
* Exposer l’API Spring Boot vers l’extérieur du cluster.
* Vérifier le fonctionnement et observer les pods.

## Scénario
Une petite API REST Spring Boot expose un endpoint /api/hello qui retourne un message JSON.
**Objectif :** déployer cette API sur Kubernetes et l’exposer via un Service de type NodePort.

## Pré-requis techniques
* Java 17 ou 21 installé.
* Maven installé.
* Docker installé et en fonctionnement.
* Minikube ou autre cluster Kubernetes local (kind, k3d, etc.).
* kubectl configuré pour accéder au cluster.
Les exemples ci-dessous utilisent Minikube.

## Création du projet 
<img width="477" height="470" alt="Capture d&#39;écran 2026-01-11 183350" src="https://github.com/user-attachments/assets/cfe5fed1-e886-4510-8467-239a5010f58d" />

## Exécution 
<img width="862" height="458" alt="Capture d&#39;écran 2026-01-11 183908" src="https://github.com/user-attachments/assets/251068b0-17a7-467f-a5bf-3037fde7a0a4" />
<img width="868" height="453" alt="Capture d&#39;écran 2026-01-11 183952" src="https://github.com/user-attachments/assets/34c62829-9a4b-4442-8390-b2d1e8f7a304" />
<img width="864" height="455" alt="Capture d&#39;écran 2026-01-11 184034" src="https://github.com/user-attachments/assets/23dc5afc-d2de-4560-ac61-ec83dfba55cf" />
<img width="866" height="459" alt="Capture d&#39;écran 2026-01-11 184047" src="https://github.com/user-attachments/assets/7c1f0d56-8366-45ee-8e75-52c8cf9724de" />
<img width="807" height="474" alt="Capture d&#39;écran 2026-01-11 184120" src="https://github.com/user-attachments/assets/9d0a74ec-d594-4b51-b285-0afcac7627f6" />
<img width="814" height="468" alt="Capture d&#39;écran 2026-01-11 184133" src="https://github.com/user-attachments/assets/8e45af30-bdd8-47c2-b817-0ac25d3792d6" />
<img width="960" height="500" alt="Capture d&#39;écran 2026-01-11 191804" src="https://github.com/user-attachments/assets/b8fd8006-1544-4a4f-b901-759016512101" />
<img width="960" height="499" alt="Capture d&#39;écran 2026-01-11 191838" src="https://github.com/user-attachments/assets/49f9637f-b56e-4036-9b43-e391aae02532" />
<img width="863" height="459" alt="Capture d&#39;écran 2026-01-11 191907" src="https://github.com/user-attachments/assets/61781f5e-e646-4237-8fba-25118871b287" />
<img width="960" height="477" alt="Capture d&#39;écran 2026-01-11 192000" src="https://github.com/user-attachments/assets/91665de3-80d5-480c-a4a1-a7be1889cce0" />

### Minikube
<img width="960" height="465" alt="Capture d&#39;écran 2026-01-11 192749" src="https://github.com/user-attachments/assets/a1384f18-5792-4e2d-8e2f-eaa3015b0596" />
<img width="412" height="452" alt="Capture d&#39;écran 2026-01-11 193226" src="https://github.com/user-attachments/assets/4d93d036-5e9d-42d7-affb-0800885b8771" />
<img width="960" height="502" alt="Capture d&#39;écran 2026-01-11 193607" src="https://github.com/user-attachments/assets/0a66a4ca-e2b7-4909-a6a0-02f7ffecac9c" />
<img width="960" height="501" alt="Capture d&#39;écran 2026-01-11 195846" src="https://github.com/user-attachments/assets/e77a9318-4667-4881-bba6-058927e63eeb" />
<img width="960" height="499" alt="Capture d&#39;écran 2026-01-11 194340" src="https://github.com/user-attachments/assets/6e1d473c-72d1-4903-999e-da8b52a57add" />
<img width="960" height="499" alt="Capture d&#39;écran 2026-01-11 194658" src="https://github.com/user-attachments/assets/65c9eff3-7d44-4b4d-831d-6d3c5d98e432" />
<img width="960" height="495" alt="Capture d&#39;écran 2026-01-11 195224" src="https://github.com/user-attachments/assets/2935d51a-ba43-4adb-ad8b-1be8d0e6b900" />
<img width="960" height="494" alt="Capture d&#39;écran 2026-01-11 195957" src="https://github.com/user-attachments/assets/8ce20f65-93f0-4673-83a8-87982d4f9ea6" />
<img width="960" height="501" alt="Capture d&#39;écran 2026-01-11 200009" src="https://github.com/user-attachments/assets/c8ca0280-e442-4319-a027-53bf4af45cf0" />

## Auteur
* Nom : BEN-LAGHFIRI Majeda
* Cours: Architecture Microservices : Conception, Déploiement et Orchestration
* Date : Janvier 2026
* Encadré par : Pr.Mohamed LACHGAR





