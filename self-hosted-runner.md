# self-hosted-runner

## error fix

runner config error: Must not run with sudo

```bash
export RUNNER_ALLOW_RUNASROOT="1"
```

## config runner as service

```bash
sudo ./svc.sh install
sudo ./svc.sh start
sudo ./svc.sh stop
sudo ./svc.sh status
sudo ./svc.sh uninstall
```
