# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Non publié

### Ajouté
- Sélecteur de sonnerie d'alerte directement dans l'application avec aperçu audio instantané dès la sélection d'une sonnerie.
- Option pour faire sonner les alertes en continu jusqu'à leur acquittement ou leur ouverture.
- Réglage d'un volume d'alerte dédié (avec curseur personnalisable), utilisant le flux d'alarme afin de garantir un son fort même si les notifications du téléphone sont basses.

## [0.2.0] - 2026-10-15

### Added
- Swipe horizontally between alert views (open, acknowledged, closed) in the alert list.

### Changed
- Team picker in settings uses Material 3 radio buttons in a wider dialog, opened from a
  navigation chevron instead of a "Change" text button.
- Notification permission and battery optimisation entries in settings are hidden once granted.
- App version is shown below the logout entry in settings.

### Fixed
- Double status bar padding at the top of screens.

## [0.1.0] - 2026-10-14

### Added
- Initial release of Jicrade, a mobile client for Jira Service Management Operations.
- Browse and manage on-call alerts (acknowledge, close, details).
- Notifications for new alerts and on-call shift tracking.

[0.2.0]: https://github.com/arnaudmorin/jicrade/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/arnaudmorin/jicrade/releases/tag/v0.1.0
