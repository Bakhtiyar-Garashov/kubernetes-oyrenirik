# Kubernetes öyrənirik youtube seriyasi 

Bu repoda Cloud and Serverless community Azerbaijan rəsmi kanalında Fəqani Hacızadə ilə başlamış olduğumuz yayımların qeyd və resurslarını tapacaqsınız.

Youtube kanalı: [CloudandServerlesscommunityAze](https://www.youtube.com/@CloudandServerlesscommunityAze)

<br/>

["Kubernetes öyrənirik" seriyası](https://www.youtube.com/playlist?list=PLtHyLYK_8dTGNf8g4Xp_qGfpdzz1IFc2Q)


## Bölümlər siyahısı

<details>
  <summary> <a name="episode-0">Kubernetes öyrənirik | E0 - Kubernetes nədir? Nə zaman kubernetes istifadə edək? Necə öyrənək?</a>
</summary>

  +  Mövzu başlıqları
        * Kubernetes nədir
        * Nə zaman istifadə edək
        * Necə öyrənək
        * Learning environment
            - minikube/kind
            - Lens IDE
  +  Youtube - https://www.youtube.com/live/Djyw44t6-gs?si=2lRQsiW9_T7KysEt
  +  Tarix 14 Yanvar, 2024 saat 18:00 (Bakı)


</details>

<details>
  <summary><a name="episode-1">Kubernetes öyrənirik | E1 - "Computer networking"-i yada salaq </a> </summary>

  +  Mövzu başlıqları
        * Layer 4 and Layer 7 networks
        * TCP/IP
        * RPC
        * HTTP 		
        * DNS 		
        * Iptables
        * SSL/TLS: One way & Mutual TLS
        * Overlay networking
        * eBPF (Cilium)
   +  Youtube (1-ci hissə) - https://youtu.be/uLvzykBG3xQ?si=3vW7wJCOiPD8CIbq
   +  Youtube (2-ci hissə) - https://youtu.be/G6ha1X9tGB4?si=lb56Fec5lHSD18Co
   +  Tarix 18 Yanvar, 2024 saat 20:40 (Bakı)
   +  Qonaq: Gökhan Geyik
   +  Resurslar:
        - [Computer Neworking - A top-down approach](https://www.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)
        - [Stanford’s Introduction to Computer Networking course](https://www.youtube.com/playlist?list=PLoCMsyE1cvdWKsLVyf6cPwCLDIZnOj0NS)
        - [What happens when you type google.com into your browser and press enter?](https://github.com/alex/what-happens-when)
        - [DNS Toys](https://www.dns.toys/)

</details>

<details>
  <summary><a name="episode-2">Kubernetes öyrənirik | E2 - "Containers" mövzusuna giriş </a></summary>

  +  Mövzu başlıqları
      * "Container" nədir ?
      * Nə üçün mövcuddur ?
      * "Virtualization" və "Sandbox"-ing, fərqliliklər
      * "OCI" (not to be confused with Oracle Cloud Infrastructure :D) 
      * "Container runtimes"
      * Container processes" (init process, pid = 1)
      * "Container layers" (docker inspect, dive)
      * "Containerization"-ı mümkün eden Linux elementleri
        * Cgroups
        * Namespaces
        * Chroot
        * Root filesystem
        * Filesystem yaradilmasi (bootstrap) (numune: deboostrap tool)

   +  Youtube  https://www.youtube.com/live/G8kakM6mPys?si=VjtCT7VExp2SMjHC
   +  Tarix 09 Fevral, 2024 saat 22:00 (Bakı)
   +  Resurslar:
        - Dumb-init for container process handling https://engineeringblog.yelp.com/2016/01/dumb-init-an-init-for-docker.html
        - What is even container ? https://jvns.ca/blog/2016/10/10/what-even-is-a-container/
        - Containers are chroot with marketing budget https://earthly.dev/blog/chroot/
        - Container Security (Liz Rice) from O'Reilly https://www.oreilly.com/library/view/container-security/9781492056690/
        - Open Container Initiative spec https://github.com/opencontainers/runtime-spec/tree/main

</details>


<details>
  <summary><a name="episode-3">Kubernetes öyrənirik | E3 - Docker, Podman ve s. </a></summary>

  +  Mövzu başlıqları
      * Docker vs podman architecture, 
      * Review an example dockerfile, 
      * Container network 
      * Compose 
      * Docker desktop, podman desktop, podman machine 
      * K8s and container runtimes, CRI-O
    
   +  Youtube  https://www.youtube.com/live/nHGat9VA_xg?si=HR4jjmb5hfKwkbCo
   +  Tarix 16 Fevral, 2024 saat (Bakı)

</details>

<details>
  <summary><a name="episode-4">Kubernetes öyrənirik | E4 - K8S giriş: Cluster arxitekturası </a></summary>

  +  Mövzu başlıqları
      * Kubernetes nədir və nə işə yarayır? 
      * Kubernetes arxitekturasına giriş 
      * Control Plane componentləri
      * Worker node componentləri 
      * Kubernetes Obyektləri və Resurslarınına giriş
    
   +  Youtube https://www.youtube.com/live/atoSUfAdvPc?si=GxO3VZjIvJkTD1FX
   +  Tarix 6 Mart, 2024 saat 21:30 (Bakı)
   +  Resurslar: https://kubernetes.io/docs/concepts/architecture/

</details>

<details>
  <summary><a name="episode-5">Kubernetes öyrənirik | E5 - Kubernetes Containers & Pods </a></summary>

  +  Mövzu başlıqları
      * Kubernetes Containers
      * Runtime class və Container Lifecycle hooks
      * Kubernetes Pods
          * Pod Lifecycle
          * Init & Sidecar Containers
          * Ephemeral containers
          * Distruptions & QOS
          * User Namespaces
    
   +  Youtube: TBD
   +  Tarix: 12 Mart, 2024 saat 20:30 (Bakı)
   +  Resurslar:
        - https://kubernetes.io/docs/concepts/containers/
        - https://kubernetes.io/docs/concepts/workloads/pods/

</details>
