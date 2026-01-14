# MinIO – Docker Compose Setup

Bu proje, **MinIO**’yu Docker Compose kullanarak hızlıca ayağa kaldırmak için hazırlanmıştır.

## 🚀 Kurulum

Docker ve Docker Compose kurulu olmalıdır.

```bash
docker compose up -d
```

## 🌐 Erişim Bilgileri

| Servis       | Adres                 |
|--------------|-----------------------|
| S3 API       | http://localhost:9000 |
| Web Console  | http://localhost:9001 |

## 🔐 Varsayılan Giriş Bilgileri

```env
MINIO_ROOT_USER=admin
MINIO_ROOT_PASSWORD=123456
```
