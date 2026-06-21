# Integration Notes

## Components

* kk-api
* kk-payments
* kk-logs

## Shared Resources

The application uses a shared directory structure under:

/opt/kijanikiosk

Shared logging is provided through:

/opt/kijanikiosk/shared/logs

Access is controlled through:

* kijanikiosk group
* ACL permissions

## Service Management

All services are managed using systemd and configured to:

* Start automatically on boot
* Restart automatically after failure

## Monitoring

Health information is written to:

/opt/kijanikiosk/health/health.json

This file can be consumed by monitoring tools.