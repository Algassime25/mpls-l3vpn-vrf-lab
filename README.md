# MPLS Layer 3 VPN & VRF Lab

## Overview | Aperçu

## Overview | Aperçu

**EN:**  
Design and implementation of an MPLS Layer 3 VPN infrastructure allowing multiple companies to securely interconnect their remote sites through a shared service provider network. Traffic is isolated using VRFs, while MP-BGP ensures route distribution between sites.

**FR :**  
Conception et mise en place d’une infrastructure MPLS Layer 3 VPN permettant à plusieurs entreprises de connecter leurs sites distants de manière sécurisée à travers un réseau fournisseur partagé. L’isolation du trafic est assurée par les VRF, tandis que MP-BGP permet la distribution des routes entre les sites.

---

## Technologies

- MPLS, LDP, CEF  
- MP-BGP (VPNv4)  
- VRF (segmentation)  
- OSPF, EIGRP (PE-CE routing)  

---

## Architecture

- P routers: MPLS core  
- PE routers: provider edge (VRF, BGP)  
- CE routers: customer edge (OSPF / EIGRP)  

---

## Value | Valeur

**EN:**  
Secure multi-site connectivity, customer isolation, and scalable service provider design.

**FR :**  
Connexion sécurisée multi-sites, isolation des clients et architecture scalable utilisée par les fournisseurs.

---

## Results | Résultats

- Intra-customer communication  
- Inter-customer isolation  
- MPLS forwarding operational  

---

## Conclusion

**EN:**  
Demonstrates a real-world service provider architecture ensuring secure and scalable connectivity.

**FR :**  
Démontre une architecture réelle permettant une connectivité sécurisée et évolutive.
