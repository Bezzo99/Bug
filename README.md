 

 ### 🇳‌🇴‌🇻‌🇦‌🇳‌ 🇸‌🇹‌🇴‌🇷‌🇪‌
🛒 Berminat????
☎️ Hubungi
📞  wa.me//6285718230420       
➥  t.me/novanthekillz
### Format Vless WS TLS

- name: Vless-Gas2-WS TLS
  server: free-akun.novan.social
  port: 443
  type: vless
  uuid: b8a57048-c645-48fc-b59e-f722b71b5816
  cipher: auto
  tls: true
  skip-cert-verify: true
  servername: free-akun.novan.social
  network: ws
  ws-opts:
    path: /vless
    headers:
      Host: free-akun.novan.social

### Format Vless WS Non TLS

- name: Vless-Gas2-WS (CDN) Non TLS
  server: free-akun.novan.social
  port: 80
  type: vless
  uuid: b8a57048-c645-48fc-b59e-f722b71b5816
  cipher: auto
  tls: false
  skip-cert-verify: false
  servername: free-akun.novan.social
  network: ws
  ws-opts:
    path: /vless
    headers:
      Host: free-akun.novan.social
  udp: true

### Format Vless gRPC (SNI)

- name: Vless-Gas2-gRPC (SNI)
  server: free-akun.novan.social
  port: 443
  type: vless
  uuid: b8a57048-c645-48fc-b59e-f722b71b5816
  cipher: auto
  tls: true
  skip-cert-verify: true
  servername: free-akun.novan.social
  network: grpc
  grpc-opts:
  grpc-mode: gun
    grpc-service-name: vless-grpc

=================================
Link Akun Vless 
==================================
Link TLS      : 
vless://b8a57048-c645-48fc-b59e-f722b71b5816@free-akun.novan.social:443?path=/vless&security=tls&encryption=none&type=ws#Gas2
==================================
Link none TLS : 
vless://b8a57048-c645-48fc-b59e-f722b71b5816@free-akun.novan.social:80?path=/vless&encryption=none&type=ws#Gas2
==================================
Link GRPC     : 
vless://b8a57048-c645-48fc-b59e-f722b71b5816@free-akun.novan.social:443?mode=gun&security=tls&encryption=none&type=grpc&serviceName=vless-grpc&sni=free-akun.novan.social#Gas2


