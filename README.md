# docker-monitoring-stack
Docker monitoring stack with Prometheus, Grafana, and Node Exporter
# 🖥️ Docker Monitoring Stack

یک استک کامل مانیتورینگ با استفاده از **Docker** و **Docker Compose** شامل:
<img width="1363" height="603" alt="image" src="https://github.com/user-attachments/assets/7bcea4cf-6cdf-4a77-98a5-1bf4d3ef54b2" />

- [**Prometheus**](https://prometheus.io/) - جمع‌آوری و ذخیره‌سازی متریک‌ها
- [**Grafana**](https://grafana.com/) - نمایش و تحلیل داده‌ها با داشبوردهای زیبا
- [**Node Exporter**](https://github.com/prometheus/node_exporter) - جمع‌آوری اطلاعات سیستمی (CPU، RAM، دیسک، شبکه)
- [**Alertmanager**](https://prometheus.io/docs/alerting/latest/alertmanager/) - مدیریت هشدارها (اختیاری)

---

## 🚀 راه‌اندازی سریع

### پیش‌نیازها
- Docker
- Docker Compose

### نصب و اجرا

```bash
# 1. کلون کردن مخزن
git clone https://github.com/fatir82/docker-monitoring-stack.git
cd docker-monitoring-stack

# 2. اجرای سرویس‌ها
docker-compose up -d

# 3. بررسی وضعیت
docker-compose ps
