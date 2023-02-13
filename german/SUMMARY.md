# Inhaltsverzeichnis
[//]: # 

[//]: #  ([Einleitung](README.md)
* [Erste Schritte](setup/getting-started/getting-started.md)
* [Devtron installieren](setup/install/README.md)
  * [Devtron mit CI/CD-Integration installieren](setup/install/install-devtron-with-cicd.md)
  * [Devtron mit CI/CD zusammen mit GitOps installieren (Argo CD)](setup/install/install-devtron-with-cicd-with-gitops.md)
  * [Devtron installieren](setup/install/install-devtron.md)
  * [Devtron auf Minikube, Microk8s, K3s, Kind installieren](setup/install/Install-devtron-on-Minikube-Microk8s-K3s-Kind.md)
  * [FAQ zur Installation](setup/install/faq-on-installation.md)
  * [Devtron deinstallieren](setup/install/uninstall-devtron.md)

 [//]: #   ([Konfigurationen](setup/configurations/configurations-overview.md)

  [//]: #  ([Installationskonfigurationen](setup/install/installation-configuration.md)

  [//]: #  ([Konfigurationen überschreiben](setup/install/override-default-devtron-installation-configs.md)

  [//]: #  ([Ingress-Setup](setup/install/ingress-setup.md)

* [Globale Konfigurationen](user-guide/global-configurations/README.md)
  * [Host URL](user-guide/global-configurations/host-url.md)
  * [GitOps](user-guide/global-configurations/gitops.md)
  * [Projekte](user-guide/global-configurations/projects.md)
  * [Cluster und Umgebungen](user-guide/global-configurations/cluster-and-environments.md)
  * [Git-Konten](user-guide/global-configurations/git-accounts.md)
  * [Container-Register](user-guide/global-configurations/docker-registries.md)

  [//]: #  ([Chart-Repositorys](user-guide/global-configurations/chart-repo.md)

  [//]: #  ([Benutzerdefinierte Charts](user-guide/global-configurations/custom-charts.md)

  [//]: #  ([SSO Login Service](user-guide/global-configurations/sso-login.md)

  [//]: #  ([Autorisierung](user-guide/global-configurations/authorization/README.md)

    [//]: #  ([Benutzerberechtigungen](user-guide/global-configurations/authorization/user-access.md)
    [//]: #  ([Berechtigungsgruppen](user-guide/global-configurations/authorization/permission-groups.md)

    [//]: #  ([API-Token](user-guide/global-configurations/authorization/api-tokens.md)

  [//]: #  ([Nachrichten verwalten](user-guide/global-configurations/manage-notification.md)
  [//]: #  ([Externe Links](user-guide/global-configurations/external-links.md)
[//]: #  ([Devtron-Upgrade](setup/upgrade/README.md)
  [//]: #  ([Devtron von Devtron UI updaten](setup/upgrade/upgrade-devtron-ui.md)
  [//]: #  ([0.5.x-0.6.x](setup/upgrade/devtron-upgrade-0.5.x-0.6.x.md)
  [//]: #  ([0.4.x-0.5.x](setup/upgrade/devtron-upgrade-0.4.x-0.5.x.md)
  [//]: #  ([0.4.x-0.4.x](setup/upgrade/devtron-upgrade-0.4.x-0.4.x.md)
  [//]: #  ([0.3.x-0.4.x](setup/upgrade/devtron-upgrade-0.3.x-0.4.x.md)
  [//]: #  ([0.3.x-0.3.x](setup/upgrade/devtron-upgrade-0.3.x-0.3.x.md)
  [//]: #  ([0.2.x-0.3.x](setup/upgrade/devtron-upgrade-0.2.x-0.3.x.md)

[//]: # (## Verbrauch)

[//]: #  ([Anwendungen](user-guide/applications.md)
  [//]: #  ([Eine neue Anwendung erstellen](user-guide/create-application.md)
  [//]: #  ([Eine bestehende Anwendung klonen](user-guide/cloning-application.md)
  [//]: #  ([Eine Beispielanwendung bereitstellen](user-guide/Deploy-sample-app/nodejs_app.md)
  [//]: #  ([App-Konfiguration](user-guide/creating-application/README.md)
  [//]: #  ([Git-Repository](user-guide/creating-application/git-material.md)

  [//]: #  ([Build-Konfiguration](user-guide/creating-application/docker-build-configuration.md)

  [//]: #  ([Vorlage für die Bereitstellung](user-guide/creating-application/deployment-template.md)

  [//]: #  ([Bereitstellung](user-guide/creating-application/deployment-template/deployment.md)

  [//]: #  ([Rollout-Bereitstellung](user-guide/creating-application/deployment-template/rollout-deployment.md)

  [//]: #  ([Job und Cronjob](user-guide/creating-application/deployment-template/job-and-cronjob.md)

  [//]: #  ([Workflow-Übersicht](user-guide/creating-application/workflow/README.md)

  [//]: #  ([CI-Pipeline](user-guide/creating-application/workflow/ci-pipeline.md)

  [//]: #  ([Pre-Build/Post-Build-Aufgaben](user-guide/creating-application/workflow/ci-build-pre-post-plugins.md)

  [//]: #  ([Build-Konfiguration überschreiben](user-guide/creating-application/container-registry-override.md)

  [//]: #  ([CI-Pipeline](user-guide/creating-application/workflow/ci-pipeline-legacy.md)

  [//]: #  ([CD-Pipeline](user-guide/creating-application/workflow/cd-pipeline.md)

  [//]: # ([Karten konfigurieren](user-guide/creating-application/config-maps.md)

  [//]: # ([Geheimnisse](user-guide/creating-application/secrets.md)

  [//]: #  ([External Secret Operator](user-guide/creating-application/eso/README.md)

  [//]: # ([AWS Secrets Manager](user-guide/creating-application/eso/aws-eso.md)

  [//]: # ([Umgebungsüberschreibungen](user-guide/creating-application/environment-overrides.md)

  [//]: #  ([Anwendung löschen](user-guide/deleting-application.md)

  [//]: #  ([Build und Bereitstellung](user-guide/deploying-application/README.md)

  [//]: #  ([CI auslösen](user-guide/deploying-application/triggering-ci.md)

  [//]: # ([CD auslösen](user-guide/deploying-application/triggering-cd.md)

  [//]: #  ([Rollback-Bereitstellung](user-guide/deploying-application/rollback-deployment.md)

  [//]: #  ([App-Details](user-guide/creating-application/app-details.md)
  [//]: #  ([Fehlersuche, Bereitstellung und Überwachung](user-guide/debugging-deployment-and-monitoring.md)
  [//]: # ([Anwendungsmetriken](user-guide/creating-application/app-metrics.md)
  [//]: #  ([Übersicht](user-guide/creating-application/overview.md)
[//]: #  ([Ressourcen-Browser](user-guide/resource-browser.md)
[//]: #  ([Charts](user-guide/deploy-chart/README.md)
  [//]: #  ([Charts-Übersicht](user-guide/deploy-chart/overview-of-charts.md)
  [//]: #  ([Bereitstellen & Beobachten](user-guide/deploy-chart/deployment-of-charts.md)
  [//]: #  ([Beispiele](user-guide/deploy-chart/examples/README.md)
  [//]: #  ([Bereitstellung von Mysql Helm Chart](user-guide/deploy-chart/examples/deploying-mysql-helm-chart.md)
  [//]: #  ([Bereitstellung von MongoDB Helm Chart](user-guide/deploy-chart/examples/deploying-mongodb-helm-chart.md)
  [//]: #  ([Chart.Gruppe](user-guide/deploy-chart/chart-group.md)
[//]: #  ([Sicherheit](user-guide/security-features.md)
[//]: #  ([Cluster](user-guide/clusters.md)
[//]: #  ([Bulk-Bearbeitung](user-guide/bulk-update.md)
[//]: #  ([Integrationen](user-guide/integrations/README.md)
[//]: #  ([Build und Bereitstellung](user-guide/integrations/build-and-deploy-ci-cd.md)
[//]: # ([GitOps](user-guide/integrations/argocd.md)
[//]: #  ([Schwachstellen-Scanning](user-guide/integrations/clair.md)
  [//]: #  ([Benachrichtigungen](user-guide/integrations/notifications.md)
  [//]: #  ([Überwachung](user-guide/integrations/grafana.md)

[//]: # (## Ressourcen)

[//]: #  ([Fehlerbehebung](FAQs/devtron-troubleshoot.md)
[//]: #  ([Anwendungsfälle](user-guide/use-cases/README.md)
  [//]: #  ([Devtron Generic Helm Chart zum Ausführen von CronJob oder One Time Job](user-guide/use-cases/devtron-generic-helm-chart-to-run-cron-job-or-one-time-job.md)
  [//]: #  ([SpringBoot mit Mysql-Datenbank verbinden](user-guide/use-cases/connect-springboot-with-mysql-database.md)
  [//]: #  ([Expressjs mit Mongodb-Datenbank verbinden](user-guide/use-cases/connect-expressjs-with-mongodb-database.md)
  [//]: #  ([Django mit Mysql-Datenbank verbinden](user-guide/use-cases/connect-django-with-mysql-database.md)
[//]: #  ([Telemetrie-Übersicht](user-guide/telemetry.md)

[//]: # (## Abgelehnt)

[//]: #  ([Hyperion](hyperion/devtron.md)
