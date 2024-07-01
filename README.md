# Generate RSA Keypair

```
openssl genpkey -algorithm RSA -pkeyopt rsa_keygen_bits:4096 -out rsa_keypair.pem
```

```
❯ openssl genpkey -algorithm RSA -pkeyopt rsa_keygen_bits:4096 -out rsa_keypair.pem

❯ cat rsa_keypair.pem                                                                                                                     ─╯
-----BEGIN PRIVATE KEY-----
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
ni31XaPm1d7o1f/J8Wln+gzax5F7Aw==
-----END PRIVATE KEY-----

```

# Inspect structure Of RSA Key

```
openssl pkey -in rsa_keypair.pem -noout -text
```

```
❯ openssl pkey -in rsa_keypair.pem -noout -text                                                                                           ─╯
Private-Key: (4096 bit, 2 primes)
modulus:
    00:b2:96:ba:5f:5f:f8:9c:b4:9a:33:bb:6f:af:db:
    46:36:2b:b5:3e:40:75:38:86:54:1c:40:0e:99:e0:
    d4:24:2a:05:07:4f:76:ae:f4:4a:7c:20:9e:10:5e:
    7f:ae:15:f0:6c:d1:1b:64:55:58:7c:1e:27:1e:48:
    fd:54:2a:be:99:a7:83:52:0d:2b:dc:a5:38:37:d3:
    e0:1b:ec:d9:c7:5e:5d:c0:ba:f2:d6:38:2a:9c:e0:
    01:32:af:6e:aa:e9:a9:69:cb:58:ac:2c:38:78:2b:
    ab:13:56:ba:6b:a9:f5:37:25:9c:3c:95:d8:2b:81:
    d8:9c:32:5f:e2:b7:2b:09:6a:1d:cc:e1:a9:1c:b2:
    dc:a2:06:e1:b4:63:9a:71:07:a9:13:1c:b9:60:f2:
    2c:e6:ee:fe:bb:4c:8e:fe:c6:7f:ba:39:c4:f0:2f:
    93:48:8c:d7:cd:34:36:20:28:f5:a3:65:68:98:3b:
    c5:2c:a7:24:40:e8:f4:14:be:0c:ff:a8:57:1f:5e:
    97:b3:b8:5a:f0:40:24:12:d9:9e:f2:42:79:70:3e:
    43:79:69:3a:87:be:f8:9f:fc:57:4c:fb:44:ad:f6:
    3c:dd:65:3e:81:76:50:ca:df:a7:f0:c6:15:66:73:
    5f:81:04:ca:d1:0a:14:87:8d:97:fd:6b:ca:b2:0c:
    0f:e3:c6:90:fe:18:14:f3:90:58:71:03:08:0a:3b:
    42:05:59:37:59:7d:51:71:0b:13:4c:4c:36:57:57:
    b0:02:95:7e:63:92:c4:b6:c0:94:6e:4e:ad:25:47:
    1c:ba:43:dd:96:ab:8e:46:ff:42:e3:18:99:98:96:
    d1:4f:80:0a:de:da:e0:a1:b1:96:ef:54:6f:10:b5:
    54:da:47:cd:33:da:96:4a:15:48:ef:29:75:b4:6d:
    61:b2:92:ab:5a:42:b8:a6:79:a0:79:7c:c7:66:d0:
    1d:4b:6e:15:9d:0a:12:e9:ca:a2:e2:a8:0e:fb:f4:
    95:19:88:0b:50:d3:d0:cd:55:ae:ca:40:fb:f5:26:
    dd:70:1c:d7:4a:9e:f6:8e:53:c2:66:db:ca:8c:95:
    6c:f3:2b:58:05:ea:81:6c:7a:71:2f:18:83:34:b3:
    50:6e:c9:a6:01:b5:95:85:b4:64:b9:1c:de:fb:ab:
    4f:c8:e3:d1:ce:b1:c2:01:5a:30:a8:9b:cc:52:70:
    9e:c6:01:63:06:e6:15:86:b5:52:ef:42:64:a0:54:
    c2:9b:a3:ec:68:e6:17:a1:64:d2:9d:e7:02:58:d1:
    f0:32:d9:44:8f:5b:fb:d7:d5:44:81:2e:fd:9f:2f:
    94:d6:44:e4:5b:e1:87:8d:98:56:92:26:8a:0f:7b:
    06:e3:b9
publicExponent: 65537 (0x10001)
privateExponent:
    28:69:c8:82:15:b7:2e:4b:06:4c:27:a1:d6:13:52:
    57:a6:db:6c:5b:6c:cb:5e:46:81:60:13:8d:c9:dd:
    67:d3:a4:70:ab:90:49:76:19:b6:ee:30:a6:b6:a3:
    c1:12:d0:e5:e7:0a:02:51:f7:e4:9a:74:32:bb:c4:
    ab:fb:c2:47:06:2b:c6:f1:19:18:64:c1:0c:8d:23:
    3d:5e:83:47:c4:f8:85:49:28:f3:c6:21:0a:7f:fc:
    75:6a:52:aa:55:97:13:4c:43:64:2e:db:96:82:17:
    44:18:8f:b6:16:6f:59:cb:e6:87:a5:47:16:4d:5b:
    65:b9:56:8e:78:f1:c1:bf:24:40:3d:5e:a6:12:69:
    b0:36:cb:73:a5:48:89:44:79:03:cc:af:bc:9b:01:
    03:3f:59:20:ac:69:fd:88:90:d5:e5:05:c6:6e:95:
    af:48:c3:fa:f9:52:38:43:dc:96:5d:b7:e6:1f:3c:
    76:e6:d9:e2:e0:74:7f:8f:24:64:e4:44:d6:e1:f2:
    85:66:76:19:c1:02:08:cb:fb:56:8a:29:6d:f7:81:
    10:63:fa:2d:46:cf:7f:70:bc:96:bc:93:a5:a4:3f:
    d0:bf:fc:fd:91:f7:25:79:a8:48:e9:a2:65:1d:3d:
    a2:f6:21:29:5d:d5:18:79:b7:c7:ce:d1:3f:2a:50:
    9b:d2:b2:b9:cb:8a:45:b3:85:8f:84:ca:eb:90:6e:
    e0:67:78:bd:69:d0:d1:fe:60:ba:37:94:24:14:59:
    7d:02:c4:43:78:72:d2:55:ed:62:3f:a7:4c:8d:e0:
    6a:5f:2a:1a:ec:41:69:15:28:c5:dc:7e:7f:d7:1f:
    53:a5:07:ad:81:2e:9d:32:08:5a:0d:20:b1:96:ff:
    cd:b1:d1:47:e0:43:9b:89:90:36:4a:1b:b2:29:b6:
    20:5d:3e:95:19:3c:f3:c2:67:4a:a3:e0:4d:f3:82:
    e0:4a:e8:ed:b9:8a:de:4d:db:27:e9:0a:5d:93:a8:
    a9:b1:da:01:3d:d8:4d:5d:a5:cd:59:4e:55:18:8d:
    83:3b:91:6f:d4:f0:9c:ae:33:09:71:81:db:a2:73:
    1c:2c:8d:44:43:37:3e:a4:a2:cc:2c:cb:cc:61:56:
    7e:f8:98:be:c5:c3:b2:23:36:7d:56:21:8d:8c:d3:
    72:76:67:61:77:0c:23:6f:b8:99:79:3e:0d:96:d3:
    6e:7a:fe:01:eb:e6:ed:be:ad:13:2b:a2:d0:c2:d5:
    e8:bc:4b:bb:1e:32:fa:b6:02:6d:13:3b:3b:5b:4f:
    02:58:66:fc:b0:7a:1a:04:73:69:e6:8b:14:f1:38:
    63:d9:1d:5a:7b:05:54:ae:3b:98:6a:50:98:b1:b1:
    05:6b
prime1:
    00:f3:dc:b0:a1:25:81:68:bb:21:e3:64:01:03:85:
    d8:41:d0:b7:b6:6d:a3:25:80:4c:e4:6c:ee:eb:83:
    2b:d6:34:2d:2d:86:66:f4:40:ee:20:af:63:0e:50:
    7e:a4:5e:46:f3:20:9b:15:66:0f:a7:ff:7c:10:8b:
    eb:e9:80:6d:85:e7:cf:1e:bf:b1:1a:51:28:d5:27:
    15:f1:44:cd:06:92:26:49:f2:8b:04:b7:6f:5d:bf:
    0c:f3:eb:67:96:ac:5c:93:d2:36:e1:57:15:19:53:
    d6:44:44:28:cc:a7:b5:58:68:1c:62:a8:b9:10:3e:
    51:db:9f:f5:ac:6f:05:db:aa:aa:97:6f:70:47:a2:
    c9:11:9f:e5:42:a7:42:e1:fc:da:60:03:19:07:ed:
    99:d8:be:25:b5:6e:fc:b9:21:e6:2d:81:c5:bb:83:
    88:57:0f:01:07:ba:cc:9d:00:61:ad:87:a1:ce:d3:
    d3:e7:8c:55:31:19:f5:ef:b7:32:fe:32:ca:42:20:
    e0:6e:ff:3a:59:24:bd:69:16:9a:8d:30:e1:68:c3:
    43:28:82:09:d3:a8:48:fa:cb:b2:e5:61:1c:bd:f3:
    d3:fc:73:8c:88:39:f8:a2:f9:53:6d:80:f6:d1:e6:
    78:3a:76:0a:77:f9:d5:0a:76:28:be:f8:92:2e:63:
    a8:3b
prime2:
    00:bb:7a:52:11:a2:3d:1a:b9:5e:08:18:c9:c4:22:
    62:b7:b3:0d:34:4c:9c:b4:c1:15:b8:33:f4:02:78:
    c8:c2:c5:a3:6a:b8:0d:c2:56:23:82:6a:e2:3b:0f:
    41:82:05:f7:f6:d7:4e:b5:28:0b:25:bf:ba:42:91:
    53:cd:ff:44:fa:f7:9f:fe:84:c3:de:1d:c1:5a:53:
    17:92:6c:3c:5f:48:b7:27:98:d9:f3:03:30:ef:7d:
    30:0d:80:7f:1d:d6:1f:15:1c:4e:ed:dd:4b:a1:e7:
    3a:99:17:91:a0:e5:7f:8a:1a:6e:18:45:c5:d0:25:
    b2:e3:e0:b9:bd:f6:be:86:fc:42:d2:93:af:30:eb:
    18:d0:7f:69:e0:6c:5e:b8:6b:8f:99:36:ba:04:b6:
    19:d9:37:b8:60:4d:cb:1d:66:eb:5d:d0:54:56:e3:
    84:2f:03:dd:b0:7e:f8:52:98:f4:55:52:31:fd:20:
    4d:05:d6:4b:4b:4e:a9:e5:f2:6a:e8:4e:da:1d:d1:
    0c:c1:dc:1b:29:78:f3:f0:ea:66:98:90:af:47:b6:
    f5:15:e6:5f:59:72:af:e3:5d:ae:be:33:42:3b:2e:
    4e:5a:6e:d3:24:6c:c9:f6:b0:ab:ee:5e:23:a2:a5:
    04:d9:6e:17:8b:68:37:62:35:54:07:08:2c:1a:97:
    98:9b
exponent1:
    00:a9:33:56:da:78:cb:71:7f:65:e4:00:5f:33:b2:
    8a:7a:1f:f7:57:fc:7a:56:6a:ce:ef:2f:26:17:02:
    cc:47:b3:ac:25:0a:3c:24:fd:68:3c:05:75:15:59:
    84:85:47:64:b3:0c:cc:8d:ec:62:b0:8d:f3:e7:07:
    2e:88:b5:33:48:d5:ae:40:07:81:3a:61:55:93:8f:
    ab:09:dc:52:e5:5c:42:74:cc:74:e8:b0:dd:f4:8d:
    ba:cf:03:66:bc:84:9b:37:75:83:de:96:2d:6d:85:
    5e:05:bf:c5:0f:3a:cd:f8:a9:44:08:b0:48:b7:9c:
    85:ef:7c:ed:58:d7:2f:99:5a:b1:42:a1:6f:a6:44:
    ac:7e:2e:13:44:4c:09:7c:03:95:01:49:24:f4:fb:
    46:e3:bc:0b:2d:f7:f4:22:00:03:55:4f:d5:82:65:
    a1:13:c6:b5:50:47:ab:f0:c3:73:02:94:39:10:e8:
    a8:fe:df:bf:bc:71:e6:d2:8c:aa:34:f5:c8:a0:59:
    6f:5f:94:77:47:a2:d6:49:34:05:c8:31:42:35:0e:
    46:6a:b4:cf:5c:ac:46:f6:bc:9f:43:c8:3d:c9:0e:
    84:e7:84:c4:dd:40:5b:e3:b8:5a:ca:7f:d0:c1:92:
    c7:98:c8:8e:3a:f0:7d:80:e4:bb:20:c6:17:a7:58:
    3e:41
exponent2:
    68:ae:aa:78:b2:30:90:65:84:fd:dc:69:7d:1c:fe:
    26:38:d2:5c:ab:92:ac:d3:4b:bf:69:33:0c:d6:48:
    b3:89:0b:f0:a1:08:fd:c4:7f:5b:69:37:1d:67:2d:
    5a:de:de:50:74:74:bc:6e:b9:9a:c0:6d:ce:91:bb:
    4b:c1:07:d1:62:c7:71:a4:cc:81:8f:f7:d0:e9:a8:
    b5:d7:bd:f6:2e:72:26:a8:10:ba:c2:c3:66:56:6e:
    a8:7b:61:7f:55:7a:51:9d:56:ed:36:ad:ee:9f:60:
    76:ef:54:1f:95:46:1b:e5:1a:28:6f:7d:3e:f6:6d:
    e7:14:2a:62:ca:0e:24:ed:62:9a:96:60:32:5e:73:
    a2:a8:22:84:6f:be:8c:17:73:3d:47:f3:a2:81:d3:
    f9:18:45:d9:70:56:c3:fa:1d:de:6a:5f:4d:8d:08:
    d7:ff:be:9f:b8:a6:0b:e8:e0:35:6c:0a:01:9f:31:
    a2:da:bf:7c:33:56:66:d1:6f:a4:7b:b3:0b:07:19:
    aa:7d:ae:a4:ff:a6:a6:95:1b:e8:80:91:7e:e7:c7:
    fe:0c:7e:9d:41:8e:b8:d4:2c:a8:83:92:ad:dc:f3:
    5f:47:96:9a:36:2c:a7:94:8a:cc:34:c0:8d:26:bb:
    88:75:12:ac:82:ea:b9:e9:b1:1b:a4:12:8c:5e:ad:
    95
coefficient:
    33:a8:10:ae:6d:05:24:c6:0e:88:78:bb:82:74:c5:
    2f:14:75:99:7d:de:e8:68:bb:d7:f8:a4:24:b5:93:
    9b:56:0a:83:de:5b:b8:f5:e1:94:8e:c3:a2:72:cd:
    9d:ad:b4:1d:03:66:cc:dd:02:9b:5f:85:c6:dc:a0:
    c6:92:5b:3b:4e:0a:83:8d:fa:3f:ea:68:4b:9b:fc:
    a6:80:c7:d5:44:04:15:1d:85:ac:69:3d:e6:27:cd:
    0c:00:f7:71:4c:67:e2:a8:19:6d:df:86:96:45:80:
    db:c2:83:5f:8d:46:c4:d8:0d:45:91:f4:c3:3a:4b:
    33:66:6d:45:57:c3:ca:58:d3:0b:df:e2:32:1c:56:
    1f:27:73:06:58:56:b4:3a:8a:c0:18:73:0e:79:48:
    d8:29:7d:b4:6e:cc:e2:7a:3b:59:48:1a:16:d1:70:
    db:83:9c:71:dd:d6:5d:b8:32:d9:2a:86:bf:f5:3b:
    3b:8b:ef:ca:b5:45:95:6b:29:a8:b3:d4:27:ef:09:
    9a:4b:27:8b:6d:b5:e1:e9:f0:9c:f4:20:c8:37:de:
    61:7c:7c:58:e0:f0:02:f4:2a:01:96:66:13:cf:2a:
    16:d9:ca:e5:f4:51:18:bc:e0:9e:2d:f5:5d:a3:e6:
    d5:de:e8:d5:ff:c9:f1:69:67:fa:0c:da:c7:91:7b:
    03

```

# Extracting Public Key From Keypair

```
openssl pkey -in rsa_keypair.pem -pubout -out rsa_public_key.pem
```

# Inspeting Public Key

```
openssl pkey -pubin -in rsa_public_keypair.pem -noout -text
```

```
❯ openssl pkey -pubin -in rsa_public_keypair.pem -noout -text                                                                             
Public-Key: (4096 bit)
Modulus:
    00:b2:96:ba:5f:5f:f8:9c:b4:9a:33:bb:6f:af:db:
    46:36:2b:b5:3e:40:75:38:86:54:1c:40:0e:99:e0:
    d4:24:2a:05:07:4f:76:ae:f4:4a:7c:20:9e:10:5e:
    7f:ae:15:f0:6c:d1:1b:64:55:58:7c:1e:27:1e:48:
    fd:54:2a:be:99:a7:83:52:0d:2b:dc:a5:38:37:d3:
    e0:1b:ec:d9:c7:5e:5d:c0:ba:f2:d6:38:2a:9c:e0:
    01:32:af:6e:aa:e9:a9:69:cb:58:ac:2c:38:78:2b:
    ab:13:56:ba:6b:a9:f5:37:25:9c:3c:95:d8:2b:81:
    d8:9c:32:5f:e2:b7:2b:09:6a:1d:cc:e1:a9:1c:b2:
    dc:a2:06:e1:b4:63:9a:71:07:a9:13:1c:b9:60:f2:
    2c:e6:ee:fe:bb:4c:8e:fe:c6:7f:ba:39:c4:f0:2f:
    93:48:8c:d7:cd:34:36:20:28:f5:a3:65:68:98:3b:
    c5:2c:a7:24:40:e8:f4:14:be:0c:ff:a8:57:1f:5e:
    97:b3:b8:5a:f0:40:24:12:d9:9e:f2:42:79:70:3e:
    43:79:69:3a:87:be:f8:9f:fc:57:4c:fb:44:ad:f6:
    3c:dd:65:3e:81:76:50:ca:df:a7:f0:c6:15:66:73:
    5f:81:04:ca:d1:0a:14:87:8d:97:fd:6b:ca:b2:0c:
    0f:e3:c6:90:fe:18:14:f3:90:58:71:03:08:0a:3b:
    42:05:59:37:59:7d:51:71:0b:13:4c:4c:36:57:57:
    b0:02:95:7e:63:92:c4:b6:c0:94:6e:4e:ad:25:47:
    1c:ba:43:dd:96:ab:8e:46:ff:42:e3:18:99:98:96:
    d1:4f:80:0a:de:da:e0:a1:b1:96:ef:54:6f:10:b5:
    54:da:47:cd:33:da:96:4a:15:48:ef:29:75:b4:6d:
    61:b2:92:ab:5a:42:b8:a6:79:a0:79:7c:c7:66:d0:
    1d:4b:6e:15:9d:0a:12:e9:ca:a2:e2:a8:0e:fb:f4:
    95:19:88:0b:50:d3:d0:cd:55:ae:ca:40:fb:f5:26:
    dd:70:1c:d7:4a:9e:f6:8e:53:c2:66:db:ca:8c:95:
    6c:f3:2b:58:05:ea:81:6c:7a:71:2f:18:83:34:b3:
    50:6e:c9:a6:01:b5:95:85:b4:64:b9:1c:de:fb:ab:
    4f:c8:e3:d1:ce:b1:c2:01:5a:30:a8:9b:cc:52:70:
    9e:c6:01:63:06:e6:15:86:b5:52:ef:42:64:a0:54:
    c2:9b:a3:ec:68:e6:17:a1:64:d2:9d:e7:02:58:d1:
    f0:32:d9:44:8f:5b:fb:d7:d5:44:81:2e:fd:9f:2f:
    94:d6:44:e4:5b:e1:87:8d:98:56:92:26:8a:0f:7b:
    06:e3:b9
Exponent: 65537 (0x10001)

```