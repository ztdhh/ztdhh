port: 7890
allow-lan: true
mode: rule
log-level: info
unified-delay: true
global-client-fingerprint: chrome
dns:
  enable: true
  listen: :53
  ipv6: true
  enhanced-mode: fake-ip
  fake-ip-range: 198.18.0.1/16
  default-nameserver:
    - 223.5.5.5
    - 8.8.8.8
  nameserver:
    - https://dns.alidns.com/dns-query
    - https://doh.pub/dns-query
  fallback:
    - https://1.0.0.1/dns-query
    - tls://dns.google
  fallback-filter:
    geoip: true
    geoip-code: CN
    ipcidr:
      - 240.0.0.0/4
proxies:
  - name: 节点1
    type: vmess
    server: 23.227.39.12
    port: 8080
    cipher: auto
    uuid: 34c0bb5e-c120-432d-9c58-bd7d82c7397b
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: uh-lawyers-instruments-kernel.trycloudflare.com
    network: ws
    ws-opts:
      path: 34c0bb5e-c120-432d-9c58-bd7d82c7397b-vm
      headers:
        host: uh-lawyers-instruments-kernel.trycloudflare.com
  - name: 节点2
    type: vmess
    server: 23.227.39.24
    port: 8080
    cipher: auto
    uuid: 9258153a-dc97-4e39-9037-009abfc4fed0
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: per-essex-patterns-bowling.trycloudflare.com
    network: ws
    ws-opts:
      path: 9258153a-dc97-4e39-9037-009abfc4fed0-vm
      headers:
        host: per-essex-patterns-bowling.trycloudflare.com
  - name: 节点3
    type: vmess
    server: 23.227.39.23
    port: 8080
    cipher: auto
    uuid: 9b196b50-37f2-4f4b-b175-06273adc6207
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: championship-bidding-oxygen-brochure.trycloudflare.com
    network: ws
    ws-opts:
      path: 9b196b50-37f2-4f4b-b175-06273adc6207-vm
      headers:
        host: championship-bidding-oxygen-brochure.trycloudflare.com
  - name: 节点4
    type: vmess
    server: 23.227.39.45
    port: 8080
    cipher: auto
    uuid: 55021a7c-bd6c-418e-be95-ceac8ba27b45
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: widescreen-instruction-breakdown-postage.trycloudflare.com
    network: ws
    ws-opts:
      path: 55021a7c-bd6c-418e-be95-ceac8ba27b45-vm
      headers:
        host: widescreen-instruction-breakdown-postage.trycloudflare.com
  - name: 节点5
    type: ss
    server: 62.204.54.81
    port: 44550
    cipher: 2022-blake3-chacha20-poly1305
    password: 5IH4rBauUuOT4VpAshgMPMSQ3Tf+oJjDY/jEDbIel2Q=
    plugin: shadow-tls
    plugin-opts:
      host: nijigen-works.jp
      password: FHDLxKgzbcDCPmijble8uT1gddgBmOxA1XXeDgyqgGc=
      version: 3
  - name: 节点6
    type: hysteria2
    server: 64.110.25.11
    port: "33337"
    password: dongtaiwang.com
    fast-open: true
    sni: www.bing.com
    skip-cert-verify: true
  - name: 节点7
    type: vmess
    server: fbi.gov
    port: 8080
    cipher: auto
    uuid: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: pcs-referenced-camera-concerns.trycloudflare.com
    network: ws
    ws-opts:
      path: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96-vm
      headers:
        host: pcs-referenced-camera-concerns.trycloudflare.com
  - name: 节点8
    type: vmess
    server: fbi.gov
    port: 8080
    cipher: auto
    uuid: ef8c954e-014f-4b36-8273-9b5086afab34
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: bibliographic-sword-sequence-advertisers.trycloudflare.com
    network: ws
    ws-opts:
      path: ef8c954e-014f-4b36-8273-9b5086afab34-vm
      headers:
        host: bibliographic-sword-sequence-advertisers.trycloudflare.com
  - name: 节点9
    type: vmess
    server: fbi.gov
    port: 8080
    cipher: auto
    uuid: 028c8131-9e3e-4836-94ac-ea7f24d4d05a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: nest-emily-healing-h.trycloudflare.com
    network: ws
    ws-opts:
      path: 028c8131-9e3e-4836-94ac-ea7f24d4d05a-vm
      headers:
        host: nest-emily-healing-h.trycloudflare.com
  - name: 节点10
    type: vmess
    server: fbi.gov
    port: 8080
    cipher: auto
    uuid: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: larger-marketing-amounts-skin.trycloudflare.com
    network: ws
    ws-opts:
      path: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a-vm
      headers:
        host: larger-marketing-amounts-skin.trycloudflare.com
  - name: 节点11
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: ef8c954e-014f-4b36-8273-9b5086afab34
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: bibliographic-sword-sequence-advertisers.trycloudflare.com
    network: ws
    ws-opts:
      path: ef8c954e-014f-4b36-8273-9b5086afab34-vm
      headers:
        host: bibliographic-sword-sequence-advertisers.trycloudflare.com
  - name: 节点12
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 028c8131-9e3e-4836-94ac-ea7f24d4d05a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: nest-emily-healing-h.trycloudflare.com
    network: ws
    ws-opts:
      path: 028c8131-9e3e-4836-94ac-ea7f24d4d05a-vm
      headers:
        host: nest-emily-healing-h.trycloudflare.com
  - name: 节点13
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: pcs-referenced-camera-concerns.trycloudflare.com
    network: ws
    ws-opts:
      path: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96-vm
      headers:
        host: pcs-referenced-camera-concerns.trycloudflare.com
  - name: 节点14
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: larger-marketing-amounts-skin.trycloudflare.com
    network: ws
    ws-opts:
      path: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a-vm
      headers:
        host: larger-marketing-amounts-skin.trycloudflare.com
  - name: 节点15
    type: vmess
    server: yh2.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: ef8c954e-014f-4b36-8273-9b5086afab34
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: bibliographic-sword-sequence-advertisers.trycloudflare.com
    network: ws
    ws-opts:
      path: ef8c954e-014f-4b36-8273-9b5086afab34-vm
      headers:
        host: bibliographic-sword-sequence-advertisers.trycloudflare.com
  - name: 节点16
    type: vmess
    server: yh2.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 028c8131-9e3e-4836-94ac-ea7f24d4d05a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: nest-emily-healing-h.trycloudflare.com
    network: ws
    ws-opts:
      path: 028c8131-9e3e-4836-94ac-ea7f24d4d05a-vm
      headers:
        host: nest-emily-healing-h.trycloudflare.com
  - name: 节点17
    type: vmess
    server: yh2.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: pcs-referenced-camera-concerns.trycloudflare.com
    network: ws
    ws-opts:
      path: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96-vm
      headers:
        host: pcs-referenced-camera-concerns.trycloudflare.com
  - name: 节点18
    type: vmess
    server: yh3.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: larger-marketing-amounts-skin.trycloudflare.com
    network: ws
    ws-opts:
      path: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a-vm
      headers:
        host: larger-marketing-amounts-skin.trycloudflare.com
  - name: 节点19
    type: vmess
    server: yh3.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: ef8c954e-014f-4b36-8273-9b5086afab34
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: bibliographic-sword-sequence-advertisers.trycloudflare.com
    network: ws
    ws-opts:
      path: ef8c954e-014f-4b36-8273-9b5086afab34-vm
      headers:
        host: bibliographic-sword-sequence-advertisers.trycloudflare.com
  - name: 节点20
    type: vmess
    server: yh3.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 028c8131-9e3e-4836-94ac-ea7f24d4d05a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: nest-emily-healing-h.trycloudflare.com
    network: ws
    ws-opts:
      path: 028c8131-9e3e-4836-94ac-ea7f24d4d05a-vm
      headers:
        host: nest-emily-healing-h.trycloudflare.com
  - name: 节点21
    type: vmess
    server: yh3.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: pcs-referenced-camera-concerns.trycloudflare.com
    network: ws
    ws-opts:
      path: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96-vm
      headers:
        host: pcs-referenced-camera-concerns.trycloudflare.com
  - name: 节点22
    type: vmess
    server: yh3.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: larger-marketing-amounts-skin.trycloudflare.com
    network: ws
    ws-opts:
      path: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a-vm
      headers:
        host: larger-marketing-amounts-skin.trycloudflare.com
  - name: 节点23
    type: hysteria
    server: 167.160.91.115
    port: "41189"
    auth_str: bWAwIqINo7XDm1fUlXQGBifVIXoYs1ylgVKqWFKzK1XyDKuwNF
    up: 11
    down: 55
    fast-open: true
    protocol: udp
    sni: www.amazon.cn
    skip-cert-verify: true
    alpn:
      - h3
  - name: 节点24
    type: hysteria
    server: 51.158.54.46
    port: "55396"
    auth_str: dongtaiwang.com
    up: 11
    down: 55
    fast-open: true
    protocol: udp
    sni: youku.com
    skip-cert-verify: true
    alpn:
      - h3
  - name: 节点25
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 34c0bb5e-c120-432d-9c58-bd7d82c7397b
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: uh-lawyers-instruments-kernel.trycloudflare.com
    network: ws
    ws-opts:
      path: 34c0bb5e-c120-432d-9c58-bd7d82c7397b-vm
      headers:
        host: uh-lawyers-instruments-kernel.trycloudflare.com
  - name: 节点26
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 9258153a-dc97-4e39-9037-009abfc4fed0
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: per-essex-patterns-bowling.trycloudflare.com
    network: ws
    ws-opts:
      path: 9258153a-dc97-4e39-9037-009abfc4fed0-vm
      headers:
        host: per-essex-patterns-bowling.trycloudflare.com
  - name: 节点27
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 9b196b50-37f2-4f4b-b175-06273adc6207
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: championship-bidding-oxygen-brochure.trycloudflare.com
    network: ws
    ws-opts:
      path: 9b196b50-37f2-4f4b-b175-06273adc6207-vm
      headers:
        host: championship-bidding-oxygen-brochure.trycloudflare.com
  - name: 节点28
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 55021a7c-bd6c-418e-be95-ceac8ba27b45
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: widescreen-instruction-breakdown-postage.trycloudflare.com
    network: ws
    ws-opts:
      path: 55021a7c-bd6c-418e-be95-ceac8ba27b45-vm
      headers:
        host: widescreen-instruction-breakdown-postage.trycloudflare.com
  - name: 节点29
    type: hysteria
    server: 173.234.25.50
    port: 1992
    auth_str: dongtaiwang.com
    up: 11
    down: 55
    fast-open: true
    protocol: udp
    sni: bing.com
    skip-cert-verify: true
    alpn:
      - h3
  - name: 节点30
    type: vmess
    server: 23.227.38.23
    port: 8080
    cipher: auto
    uuid: 34c0bb5e-c120-432d-9c58-bd7d82c7397b
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: uh-lawyers-instruments-kernel.trycloudflare.com
    network: ws
    ws-opts:
      path: 34c0bb5e-c120-432d-9c58-bd7d82c7397b-vm
      headers:
        host: uh-lawyers-instruments-kernel.trycloudflare.com
  - name: 节点31
    type: vmess
    server: 23.227.38.44
    port: 8080
    cipher: auto
    uuid: 55021a7c-bd6c-418e-be95-ceac8ba27b45
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: widescreen-instruction-breakdown-postage.trycloudflare.com
    network: ws
    ws-opts:
      path: 55021a7c-bd6c-418e-be95-ceac8ba27b45-vm
      headers:
        host: widescreen-instruction-breakdown-postage.trycloudflare.com
  - name: 节点32
    type: vmess
    server: 23.227.38.22
    port: 8080
    cipher: auto
    uuid: 9258153a-dc97-4e39-9037-009abfc4fed0
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: per-essex-patterns-bowling.trycloudflare.com
    network: ws
    ws-opts:
      path: 9258153a-dc97-4e39-9037-009abfc4fed0-vm
      headers:
        host: per-essex-patterns-bowling.trycloudflare.com
  - name: 节点33
    type: vmess
    server: 23.227.38.11
    port: 8080
    cipher: auto
    uuid: 9b196b50-37f2-4f4b-b175-06273adc6207
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: championship-bidding-oxygen-brochure.trycloudflare.com
    network: ws
    ws-opts:
      path: 9b196b50-37f2-4f4b-b175-06273adc6207-vm
      headers:
        host: championship-bidding-oxygen-brochure.trycloudflare.com
  - name: 节点34
    type: vmess
    server: 162.159.153.11
    port: 8080
    cipher: auto
    uuid: 34c0bb5e-c120-432d-9c58-bd7d82c7397b
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: uh-lawyers-instruments-kernel.trycloudflare.com
    network: ws
    ws-opts:
      path: 5f7934bf-a228-49a7-9572-5ce4377c34d5-vm
      headers:
        host: uh-lawyers-instruments-kernel.trycloudflare.com
  - name: 节点35
    type: vmess
    server: 162.159.134.23
    port: 8080
    cipher: auto
    uuid: 9b196b50-37f2-4f4b-b175-06273adc6207
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: championship-bidding-oxygen-brochure.trycloudflare.com
    network: ws
    ws-opts:
      path: 9b196b50-37f2-4f4b-b175-06273adc6207-vm
      headers:
        host: championship-bidding-oxygen-brochure.trycloudflare.com
  - name: 节点36
    type: vmess
    server: 162.159.137.31
    port: 8080
    cipher: auto
    uuid: 9258153a-dc97-4e39-9037-009abfc4fed0
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: per-essex-patterns-bowling.trycloudflare.com
    network: ws
    ws-opts:
      path: 34c0bb5e-c120-432d-9c58-bd7d82c7397b-vm
      headers:
        host: per-essex-patterns-bowling.trycloudflare.com
  - name: 节点37
    type: vmess
    server: 162.159.130.208
    port: 8080
    cipher: auto
    uuid: 55021a7c-bd6c-418e-be95-ceac8ba27b45
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: widescreen-instruction-breakdown-postage.trycloudflare.com
    network: ws
    ws-opts:
      path: 55021a7c-bd6c-418e-be95-ceac8ba27b45-vm
      headers:
        host: widescreen-instruction-breakdown-postage.trycloudflare.com
  - name: 节点38
    type: vmess
    server: yh1.dtku41.xyz
    port: 8080
    cipher: auto
    uuid: 34c0bb5e-c120-432d-9c58-bd7d82c7397b
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: uh-lawyers-instruments-kernel.trycloudflare.com
    network: ws
    ws-opts:
      path: 34c0bb5e-c120-432d-9c58-bd7d82c7397b-vm
      headers:
        host: uh-lawyers-instruments-kernel.trycloudflare.com
  - name: 节点39
    type: vmess
    server: yh1.dtku41.xyz
    port: 8080
    cipher: auto
    uuid: 9b196b50-37f2-4f4b-b175-06273adc6207
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: championship-bidding-oxygen-brochure.trycloudflare.com
    network: ws
    ws-opts:
      path: 9b196b50-37f2-4f4b-b175-06273adc6207-vm
      headers:
        host: championship-bidding-oxygen-brochure.trycloudflare.com
  - name: 节点40
    type: vmess
    server: yh1.dtku41.xyz
    port: 8080
    cipher: auto
    uuid: 9258153a-dc97-4e39-9037-009abfc4fed0
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: per-essex-patterns-bowling.trycloudflare.com
    network: ws
    ws-opts:
      path: 9258153a-dc97-4e39-9037-009abfc4fed0-vm
      headers:
        host: per-essex-patterns-bowling.trycloudflare.com
  - name: 节点41
    type: vmess
    server: yh1.dtku41.xyz
    port: 8080
    cipher: auto
    uuid: 55021a7c-bd6c-418e-be95-ceac8ba27b45
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: widescreen-instruction-breakdown-postage.trycloudflare.com
    network: ws
    ws-opts:
      path: 55021a7c-bd6c-418e-be95-ceac8ba27b45-vm
      headers:
        host: widescreen-instruction-breakdown-postage.trycloudflare.com
  - name: 节点42
    type: vmess
    server: yh2.dtku41.xyz
    port: 8080
    cipher: auto
    uuid: 34c0bb5e-c120-432d-9c58-bd7d82c7397b
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: uh-lawyers-instruments-kernel.trycloudflare.com
    network: ws
    ws-opts:
      path: 34c0bb5e-c120-432d-9c58-bd7d82c7397b-vm
      headers:
        host: uh-lawyers-instruments-kernel.trycloudflare.com
  - name: 节点43
    type: vmess
    server: yh2.dtku41.xyz
    port: 8080
    cipher: auto
    uuid: 9b196b50-37f2-4f4b-b175-06273adc6207
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: championship-bidding-oxygen-brochure.trycloudflare.com
    network: ws
    ws-opts:
      path: 9b196b50-37f2-4f4b-b175-06273adc6207-vm
      headers:
        host: championship-bidding-oxygen-brochure.trycloudflare.com
  - name: 节点44
    type: vmess
    server: yh2.dtku41.xyz
    port: 8080
    cipher: auto
    uuid: 9258153a-dc97-4e39-9037-009abfc4fed0
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: per-essex-patterns-bowling.trycloudflare.com
    network: ws
    ws-opts:
      path: 9258153a-dc97-4e39-9037-009abfc4fed0-vm
      headers:
        host: per-essex-patterns-bowling.trycloudflare.com
  - name: 节点45
    type: vmess
    server: yh2.dtku41.xyz
    port: 8080
    cipher: auto
    uuid: 55021a7c-bd6c-418e-be95-ceac8ba27b45
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: widescreen-instruction-breakdown-postage.trycloudflare.com
    network: ws
    ws-opts:
      path: 55021a7c-bd6c-418e-be95-ceac8ba27b45-vm
      headers:
        host: widescreen-instruction-breakdown-postage.trycloudflare.com
  - name: 节点46
    type: vless
    server: yh6.dtku41.xyz
    port: 443
    uuid: ebfdccb6-7416-4b6e-860d-98587344d500
    tls: true
    skip-cert-verify: true
    servername: lg1.freessr2.xyz
    network: ws
    cipher: auto
    alterId: 0
    ws-opts:
      path: /xyakws
      headers:
        host: lg1.freessr2.xyz
    client-fingerprint: chrome
  - name: 节点47
    type: hysteria2
    server: 51.159.77.198
    port: "53967"
    password: dongtaiwang.com
    fast-open: true
    sni: www.bing.com
    skip-cert-verify: true
  - name: 节点48
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: pcs-referenced-camera-concerns.trycloudflare.com
    network: ws
    ws-opts:
      path: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96-vm
      headers:
        host: pcs-referenced-camera-concerns.trycloudflare.com
  - name: 节点49
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: ef8c954e-014f-4b36-8273-9b5086afab34
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: bibliographic-sword-sequence-advertisers.trycloudflare.com
    network: ws
    ws-opts:
      path: ef8c954e-014f-4b36-8273-9b5086afab34-vm
      headers:
        host: bibliographic-sword-sequence-advertisers.trycloudflare.com
  - name: 节点50
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 028c8131-9e3e-4836-94ac-ea7f24d4d05a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: nest-emily-healing-h.trycloudflare.com
    network: ws
    ws-opts:
      path: 028c8131-9e3e-4836-94ac-ea7f24d4d05a-vm
      headers:
        host: nest-emily-healing-h.trycloudflare.com
  - name: 节点51
    type: vmess
    server: yh1.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: larger-marketing-amounts-skin.trycloudflare.com
    network: ws
    ws-opts:
      path: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a-vm
      headers:
        host: larger-marketing-amounts-skin.trycloudflare.com
  - name: 节点52
    type: vmess
    server: yh2.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: ef8c954e-014f-4b36-8273-9b5086afab34
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: bibliographic-sword-sequence-advertisers.trycloudflare.com
    network: ws
    ws-opts:
      path: ef8c954e-014f-4b36-8273-9b5086afab34-vm
      headers:
        host: bibliographic-sword-sequence-advertisers.trycloudflare.com
  - name: 节点53
    type: vmess
    server: yh2.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 028c8131-9e3e-4836-94ac-ea7f24d4d05a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: nest-emily-healing-h.trycloudflare.com
    network: ws
    ws-opts:
      path: 028c8131-9e3e-4836-94ac-ea7f24d4d05a-vm
      headers:
        host: nest-emily-healing-h.trycloudflare.com
  - name: 节点54
    type: vmess
    server: yh2.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: pcs-referenced-camera-concerns.trycloudflare.com
    network: ws
    ws-opts:
      path: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96-vm
      headers:
        host: pcs-referenced-camera-concerns.trycloudflare.com
  - name: 节点55
    type: vmess
    server: yh3.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: larger-marketing-amounts-skin.trycloudflare.com
    network: ws
    ws-opts:
      path: 82cb93a3-65a9-4dac-a2a7-d997b6c26d6a-vm
      headers:
        host: larger-marketing-amounts-skin.trycloudflare.com
  - name: 节点56
    type: vmess
    server: yh3.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: ef8c954e-014f-4b36-8273-9b5086afab34
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: bibliographic-sword-sequence-advertisers.trycloudflare.com
    network: ws
    ws-opts:
      path: ef8c954e-014f-4b36-8273-9b5086afab34-vm
      headers:
        host: bibliographic-sword-sequence-advertisers.trycloudflare.com
  - name: 节点57
    type: vmess
    server: yh3.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: 028c8131-9e3e-4836-94ac-ea7f24d4d05a
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: nest-emily-healing-h.trycloudflare.com
    network: ws
    ws-opts:
      path: 028c8131-9e3e-4836-94ac-ea7f24d4d05a-vm
      headers:
        host: nest-emily-healing-h.trycloudflare.com
  - name: 节点58
    type: vmess
    server: yh3.freeh1.xyz
    port: 8080
    cipher: auto
    uuid: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96
    alterId: 0
    tls: false
    skip-cert-verify: true
    servername: pcs-referenced-camera-concerns.trycloudflare.com
    network: ws
    ws-opts:
      path: d9c5ec6a-a8d8-4732-8447-56fbd2f93e96-vm
      headers:
        host: pcs-referenced-camera-concerns.trycloudflare.com
  - name: 节点59
    type: hysteria
    server: 173.234.25.52
    port: "48919"
    auth_str: dongtaiwang.com
    up: 11
    down: 55
    fast-open: true
    protocol: udp
    sni: bing.com
    skip-cert-verify: true
    alpn:
      - h3
  - name: 节点60
    type: hysteria
    server: www.dtku50.xyz
    port: 18470
    sni: www.amazon.cn
    skip-cert-verify: true
    alpn:
      - h3
    protocol: udp
    auth_str: dongtaiwang.com
    up: 2
    down: 10
  - name: 节点61
    type: hysteria2
    server: 51.159.77.153
    port: 33390
    password: dongtaiwang.com
    alpn:
      - h3
    sni: bing.com
    skip-cert-verify: true
    up: 11 Mbps
    down: 55 Mbps
  - name: 节点62
    type: hysteria2
    server: 62.210.103.0
    port: "22483"
    password: dongtaiwang.com
    fast-open: true
    sni: www.bing.com
    skip-cert-verify: true
  - name: 节点63
    type: vless
    server: yh1.dtku41.xyz
    port: 443
    uuid: ebfdccb6-7416-4b6e-860d-98587344d500
    tls: true
    skip-cert-verify: true
    servername: lg1.freessr2.xyz
    network: ws
    cipher: auto
    alterId: 0
    ws-opts:
      path: /xyakws
      headers:
        host: lg1.freessr2.xyz
    client-fingerprint: chrome
  - name: 节点64
    type: vless
    server: fbi.gov
    port: 443
    uuid: ebfdccb6-7416-4b6e-860d-98587344d500
    tls: true
    skip-cert-verify: true
    servername: lg1.freessr2.xyz
    network: ws
    cipher: auto
    alterId: 0
    ws-opts:
      path: /xyakws
      headers:
        host: lg1.freessr2.xyz
    client-fingerprint: chrome
  - name: 节点65
    type: hysteria
    server: www.dtku40.xyz
    port: "18490"
    auth_str: dongtaiwang.com
    up: 11
    down: 55
    fast-open: true
    protocol: udp
    sni: bing.com
    skip-cert-verify: true
    alpn:
      - h3
  - name: 节点66
    type: hysteria
    server: www.dtku50.xyz
    port: 11229
    auth_str: dongtaiwang.com
    up: 11
    down: 55
    fast-open: true
    protocol: udp
    sni: bing.com
    skip-cert-verify: true
    alpn:
      - h3
  - name: 节点67
    type: hysteria
    server: www2.dtku48.xyz
    port: 22334
    auth-str: dongtaiwang.com
    alpn:
      - h3
    protocol: udp
    up: 11 Mbps
    down: 55 Mbps
    skip-cert-verify: true
  - name: 节点68
    type: hysteria
    server: 173.234.25.52
    port: "30072"
    auth_str: dongtaiwang.com
    up: 11
    down: 55
    fast-open: true
    protocol: udp
    sni: bing.com
    skip-cert-verify: true
    alpn:
      - h3
proxy-groups:
  - name: 节点选择
    type: select
    proxies:
      - ⚖️ 负载均衡-轮询
      - ⚖️ 负载均衡-散列
      - 自动选择
      - DIRECT
      - 节点1
      - 节点2
      - 节点3
      - 节点4
      - 节点5
      - 节点6
      - 节点7
      - 节点8
      - 节点9
      - 节点10
      - 节点11
      - 节点12
      - 节点13
      - 节点14
      - 节点15
      - 节点16
      - 节点17
      - 节点18
      - 节点19
      - 节点20
      - 节点21
      - 节点22
      - 节点23
      - 节点24
      - 节点25
      - 节点26
      - 节点27
      - 节点28
      - 节点29
      - 节点30
      - 节点31
      - 节点32
      - 节点33
      - 节点34
      - 节点35
      - 节点36
      - 节点37
      - 节点38
      - 节点39
      - 节点40
      - 节点41
      - 节点42
      - 节点43
      - 节点44
      - 节点45
      - 节点46
      - 节点47
      - 节点48
      - 节点49
      - 节点50
      - 节点51
      - 节点52
      - 节点53
      - 节点54
      - 节点55
      - 节点56
      - 节点57
      - 节点58
      - 节点59
      - 节点60
      - 节点61
      - 节点62
      - 节点63
      - 节点64
      - 节点65
      - 节点66
      - 节点67
      - 节点68
  - name: 自动选择
    type: url-test
    url: http://www.gstatic.com/generate_204
    interval: 300
    tolerance: 50
    proxies:
      - 节点1
      - 节点2
      - 节点3
      - 节点4
      - 节点5
      - 节点6
      - 节点7
      - 节点8
      - 节点9
      - 节点10
      - 节点11
      - 节点12
      - 节点13
      - 节点14
      - 节点15
      - 节点16
      - 节点17
      - 节点18
      - 节点19
      - 节点20
      - 节点21
      - 节点22
      - 节点23
      - 节点24
      - 节点25
      - 节点26
      - 节点27
      - 节点28
      - 节点29
      - 节点30
      - 节点31
      - 节点32
      - 节点33
      - 节点34
      - 节点35
      - 节点36
      - 节点37
      - 节点38
      - 节点39
      - 节点40
      - 节点41
      - 节点42
      - 节点43
      - 节点44
      - 节点45
      - 节点46
      - 节点47
      - 节点48
      - 节点49
      - 节点50
      - 节点51
      - 节点52
      - 节点53
      - 节点54
      - 节点55
      - 节点56
      - 节点57
      - 节点58
      - 节点59
      - 节点60
      - 节点61
      - 节点62
      - 节点63
      - 节点64
      - 节点65
      - 节点66
      - 节点67
      - 节点68
  - name: ⚖️ 负载均衡-散列
    type: load-balance
    url: http://www.google.com/generate_204
    interval: 300
    strategy: consistent-hashing
    proxies:
      - 节点1
      - 节点2
      - 节点3
      - 节点4
      - 节点5
      - 节点6
      - 节点7
      - 节点8
      - 节点9
      - 节点10
      - 节点11
      - 节点12
      - 节点13
      - 节点14
      - 节点15
      - 节点16
      - 节点17
      - 节点18
      - 节点19
      - 节点20
      - 节点21
      - 节点22
      - 节点23
      - 节点24
      - 节点25
      - 节点26
      - 节点27
      - 节点28
      - 节点29
      - 节点30
      - 节点31
      - 节点32
      - 节点33
      - 节点34
      - 节点35
      - 节点36
      - 节点37
      - 节点38
      - 节点39
      - 节点40
      - 节点41
      - 节点42
      - 节点43
      - 节点44
      - 节点45
      - 节点46
      - 节点47
      - 节点48
      - 节点49
      - 节点50
      - 节点51
      - 节点52
      - 节点53
      - 节点54
      - 节点55
      - 节点56
      - 节点57
      - 节点58
      - 节点59
      - 节点60
      - 节点61
      - 节点62
      - 节点63
      - 节点64
      - 节点65
      - 节点66
      - 节点67
      - 节点68
  - name: ⚖️ 负载均衡-轮询
    type: load-balance
    url: http://www.google.com/generate_204
    interval: 300
    strategy: round-robin
    proxies:
      - 节点1
      - 节点2
      - 节点3
      - 节点4
      - 节点5
      - 节点6
      - 节点7
      - 节点8
      - 节点9
      - 节点10
      - 节点11
      - 节点12
      - 节点13
      - 节点14
      - 节点15
      - 节点16
      - 节点17
      - 节点18
      - 节点19
      - 节点20
      - 节点21
      - 节点22
      - 节点23
      - 节点24
      - 节点25
      - 节点26
      - 节点27
      - 节点28
      - 节点29
      - 节点30
      - 节点31
      - 节点32
      - 节点33
      - 节点34
      - 节点35
      - 节点36
      - 节点37
      - 节点38
      - 节点39
      - 节点40
      - 节点41
      - 节点42
      - 节点43
      - 节点44
      - 节点45
      - 节点46
      - 节点47
      - 节点48
      - 节点49
      - 节点50
      - 节点51
      - 节点52
      - 节点53
      - 节点54
      - 节点55
      - 节点56
      - 节点57
      - 节点58
      - 节点59
      - 节点60
      - 节点61
      - 节点62
      - 节点63
      - 节点64
      - 节点65
      - 节点66
      - 节点67
      - 节点68
rules:
  - DOMAIN,clash.razord.top,DIRECT
  - DOMAIN,yacd.haishan.me,DIRECT
  - GEOIP,LAN,DIRECT
  - GEOIP,CN,DIRECT
  - MATCH,节点选择
proxy-providers: {}
rule-providers: {}
