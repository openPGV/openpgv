# OpenPGV

**Plateforme de gestion des vulnérabilités · Vulnerability Management Platform**

[Français](#français) · [English](#english)

## Français

OpenPGV est une plateforme conçue pour aider les équipes de sécurité, d’infrastructure et les responsables applicatifs à organiser la correction des vulnérabilités : comprendre les risques, créer les billets, attribuer les responsabilités et suivre les corrections.

Elle vise à relier les observations des outils de sécurité au travail concret des équipes, dans un espace commun.

### Ce que couvre le projet

- **Inventaire des actifs** : identifier les machines, leurs sources, leurs applications et leurs responsables.
- **Vulnérabilités et connaissances** : centraliser les détections et les informations utiles à leur correction.
- **Billets individuels et billets de groupe** : créer, attribuer et regrouper les travaux selon des règles configurables.
- **Suivi des corrections** : conserver les statuts, notes, historiques, approbations et exceptions de gouvernance.
- **Priorisation du patching** : prendre en compte la sévérité, les scores de risque, la criticité des actifs et les urgences déclarées.
- **Responsabilités** : distinguer les équipes de correction, les approbateurs, les propriétaires et les personnes à informer.
- **Modules et connecteurs** : organiser les intégrations, les configurations d’importation, les tâches planifiées et leurs journaux.
- **Accès et langues** : prévoir plusieurs sociétés, des droits par rôle et par équipe, ainsi qu’une interface en français et en anglais.

Les intégrations en cours de développement comprennent Qualys pour les données de vulnérabilité, ServiceNow pour les données d’annuaire et d’applications, et Microsoft Entra ID pour l’identité et le SSO. L’architecture doit permettre l’ajout progressif d’autres fournisseurs.

### État du projet

**OpenPGV est en cours de développement.** Ce dépôt public sert actuellement de page de présentation et de point de suivi. Il ne contient pas encore le code de la plateforme, ni de version installable.

Le code sera publié ici lorsqu’une première version sera prête à être partagée. Aucune date de publication n’est annoncée pour le moment.

### Suivre la publication

- Ajoutez une **Star** pour retrouver le projet et montrer votre intérêt.
- Pour recevoir les annonces de version via GitHub, choisissez **Watch → Custom → Releases** et activez les notifications correspondantes dans vos paramètres GitHub.
- L’ouverture du code sera annoncée sur ce dépôt à l’occasion d’une publication **Release**. Une Star seule n’active pas les notifications.

### Licence à déterminer

Les conditions de licence du code et de la documentation sont en cours de définition et seront précisées avant la publication du code. Aucune licence pour une future version n’est annoncée à ce stade.

Le modèle envisagé distingue l’usage interne de la commercialisation auprès de tiers, notamment la revente et la fourniture d’un service hébergé. Son périmètre et ses conditions restent à déterminer et à faire valider juridiquement. Cette présentation ne constitue pas une autorisation d’exploitation du futur code.

## English

OpenPGV is a vulnerability management platform designed to help security teams, infrastructure teams and application owners coordinate remediation: understand risks, create tickets, assign responsibilities and track fixes.

The project connects findings from security tools with the work performed by remediation teams in a shared workspace.

### Project scope

- **Asset inventory**: identify systems, their sources, applications and owners.
- **Vulnerabilities and knowledge**: centralize detections and the information needed for remediation.
- **Individual and grouped tickets**: create, assign and group work using configurable rules.
- **Remediation tracking**: maintain statuses, notes, history, approvals and governance exceptions.
- **Patching priorities**: consider severity, risk scores, asset criticality and manually declared urgency.
- **Responsibilities**: distinguish remediation teams, approvers, owners and stakeholders to notify.
- **Modules and connectors**: organize integrations, import configurations, scheduled tasks and logs.
- **Access and languages**: support multiple companies, role- and team-based access, and a French/English interface.

Integrations under development include Qualys for vulnerability data, ServiceNow for directory and application data, and Microsoft Entra ID for identity and SSO. The architecture is intended to accommodate additional providers over time.

### Project status

**OpenPGV is under development.** This public repository currently provides an introduction and a place to follow the project. It does not yet contain the platform source code or an installable release.

The source code will be published here when an initial version is ready to share. No release date has been announced.

### Follow the release

- **Star** the repository to bookmark the project and show your interest.
- To receive release announcements through GitHub, select **Watch → Custom → Releases** and enable the corresponding notifications in your GitHub settings.
- Source availability will be announced through a **Release** on this repository. Starring alone does not enable notifications.

### License to be determined

Licensing terms for the code and documentation are being defined and will be specified before the source code is published. No license for a future version is being announced at this stage.

The proposed model distinguishes internal use from commercialization for third parties, including resale and hosted services. Its scope and terms remain to be determined and reviewed by legal counsel. This introduction does not grant permission to use the future source code.
