Failure 1 : WEB SERVER DOWN
# Runbook: Web Server Failure

Symptoms:
- Website unavailable
- Load balancer health check failing

Steps:

1. Check EC2 instance status.
2. Review CloudWatch metrics.
3. Restart application service.
4. Reboot EC2 if required.
5. Verify health checks pass.
6. Confirm application accessibility.

Failure 2 : DATABASE FAILURE
# Runbook: Database Failure

Symptoms:
- Database connection errors
- Increased application latency

Steps:

1. Check RDS health status.
2. Review CloudWatch database metrics.
3. Restore latest automated snapshot if required.
4. Update application connection settings.
5. Verify successful connections.
6. Monitor performance after recovery.
