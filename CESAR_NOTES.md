# Cesar's notes for Algo VPN

## Multiple deployment

For deploying into multiple machines e.g. to have machines in multiple zones,
ideally need to change the usernames as it's the primary key in some wireguard
clients.

## Shutting down

For AWS EC2, just delete the corresponding CloudFormation stacks.

To delete local data, `(cd configs && rm -rf *)`.
