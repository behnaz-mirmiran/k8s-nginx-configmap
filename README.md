# k8s-nginx-configmap

این پروژه یک وب سرور NGINX را در محیط Kubernetes اجرا می‌کند و تنظیمات آن از طریق ConfigMap مدیریت می‌شود.

## 📂 ساختار فایل‌ها

- `deployment.yaml` → اجرای Nginx
- `service.yaml` → سرویس داخلی از نوع ClusterIP
- `configmap.yaml` → تنظیمات سفارشی وب سرور

## 🚀 نحوه اجرا

```bash
kubectl apply -f manifests/
