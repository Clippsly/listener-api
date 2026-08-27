# Clippsly Listener API

The official public API for **Clippsly Listener**.

Clippsly Listener is a personal music locker that lets you upload, organize and stream your own music library from anywhere. This repository contains the OpenAPI specification for the public Listener API and its compatibility layers. 

## Documentation

The complete API specification is available in:

- [`openapi.yaml`](./openapi.yaml)

The specification follows the OpenAPI standard and can be imported into tools such as Swagger UI, Postman and Insomnia.

## Listener Portal

Manage your Listener account, create App Passwords and view your storage usage at:

**https://clippsly.app**

## Base URL

```
https://listener.clippsly.app
```

## Authentication

The native Listener API uses **App Passwords**.

Supported authentication methods:

```
Authorization: Bearer <app_password>
```

or

```
X-Clippsly-App-Key: <app_password>
```

App Passwords can be created from the Listener Portal.

## Features

- Versioned REST API
- OpenAPI specification
- App Password authentication
- Personal music locker
- Album management
- Playlist management
- Folder uploads
- Playback API
- Multiple audio quality variants
- Subsonic compatibility
- Navidrome compatibility

## Versioning

The native API is available under:

```
/v1/
```

Future breaking changes will be introduced under a new version while keeping previous versions available.

## License

Licensed under the Apache License 2.0. See [LICENSE](./LICENSE) for details.
