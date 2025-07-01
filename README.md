openssl req -x509 -newkey rsa:4096 -nodes -days 365 \
  -keyout ./certs/key.pem \
  -out ./certs/cert.pem \
  -subj "/CN=10.0.0.91"
  
caddy hash-password
$2a$14$svvC9Cu.VCN18lgyMx1V4.KD1J/wFqGthg.8WSOK6ugJ.mX5dRTD2 -> admin