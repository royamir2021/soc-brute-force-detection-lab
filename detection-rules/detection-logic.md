# Detection Logic

## Event Source
Windows Security Log

## Event ID
4625 (Failed Login)

## Detection Rule
Trigger alert if:
- More than 10 failed login attempts
- Within 1 minute
- Same user or same IP

## Reason
This behavior may indicate a brute-force attack.