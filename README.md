This project provided a focused investigation into a standard HTTPS connection using Wireshark, capturing and analyzing the TLS handshake between a client system and a web server (v10.events.data.microsoft.com). The analysis confirmed the negotiation of TLS 1.3, the use of a strong cipher suite (TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384), and a valid certificate chain anchored by Microsoft’s Root CA.

By inspecting individual packets, we confirmed:

The use of Server Name Indication (SNI) in the Client Hello

The negotiation of cryptographic parameters and TLS extensions

The presentation of X.509 certificates and associated metadata

The completion of the server handshake with Server Hello Done

