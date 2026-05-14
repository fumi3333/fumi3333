# Hi there, I'm fumi (Full-stack & P2P Trust Architect)  


  I am a university student and developer passionate about building high-trust, secure, and decentralized systems. I focus on creating C2C (peer-to-peer) platforms that bridge digital security with real-world interactions, eliminating friction and visual-evaluation noise.  

    ---  

      ## Tech Stack & Skills  

        - Frontend: Next.js (App Router), React 19, TypeScript, Tailwind CSS, shadcn/ui, Flutter (Dart)  
        - Backend / BaaS: Firebase (Authentication, Cloud Firestore, Cloud Storage, Cloud Functions)  
        - Payments / API: Stripe Connect (Express Accounts, Escrow Manual Capture), OpenBD (ISBN API)  
        - Testing & Security: Zod (Schema Validation), IDOR Mitigation, Firestore Security Rules  

          ---  

            ## Key Projects  

              ### 1. [Musalink](https://github.com/fumi3333/musalink) (Live)  
              > A Closed-Loop C2C Textbook & Goods Marketplace for Students  
              - Live URL: https://musa-link.web.app/  
              - Description: Designed and deployed a complete peer-to-peer escrow marketplace. It restricts access to verified university domains and employs Stripe Connect manual capture to hold funds until in-person exchange is validated via QR code.  

                ```mermaid
                graph TD
                    Client[Client Browser]
                        Functions[Cloud Functions for Firebase]
                            Stripe[Stripe Connect]
                                Firestore[(Cloud Firestore)]

                                    Client -->|1. Request Payment Intent| Functions
                                        Functions -->|2. Create Auth Hold| Stripe
                                            Client -->|3. QR Code Scan on Delivery| Functions
                                                Functions -->|4. Capture Payment / Escrow Release| Stripe
                                                    Functions -->|5. Unlock Contact Info| Firestore
                                                    ```  

                                                      ### 2. [Voice Reader](https://github.com/fumi3333/voice_reader)  
                                                      > Cross-Platform Mobile Audio Assistant  
                                                      - Tech: Flutter, Dart, On-device Text-to-Speech  

                                                        ### 3. [ZAX / Self-OS Engine](https://github.com/fumi3333/ZAX)  
                                                        > Cognitive Architecture & Self-Analysis Toolkit  
                                                        - Tech: Python, Vector Database, Markdown Synchronization  

                                                          ---  

                                                            ## My Coding Journey (2026)  

                                                              - Commit Pacing: ~4.5 contributions per day in 2026.  
                                                              - Philosophy: "High-frequency bat swinging." Build fast, deploy securely, analyze the metrics, and iterate.  

                                                                ---  

                                                                  *Feel free to reach out via GitHub Issues or explore my codebases!*
                                                                  
