Krav:

Publikt GitHub repo  
Dockerfile.vulnerable  
Dockerfile.hardened  
Trivy scan före härdning  
Trivy scan efter härdning  
SBOM (sbom.json)  
Gatekeeper/OPA policy  
Screenshot: Gatekeeper blockar pod  

Lärdomar:

Jag fick en grundläggande förståelse för hur containers används och fungerar, och hur man kan aktivt arbeta för att göra dem säkrare då de från grunden är väldigt sårbara.  
SBOM är viktigt för det kan hjälpa till med att identifiera sårbarheter, nya som gamla, i komponenter eller bibliotek man använder i sina projekt. Genom att redan ha allt uppskrivet i en lista streamlinar man arbetet då man annars hade behövt gå över allt för sig.  
Gatekeeper policy-enforcement "automatiserar"(kanske inte rätt ord) väl på sätt och vis härdandet av ett projekt genom att automatiskt blockera konfigurationer som bryter mot säkerhetspolicyn. Det låter en på sätt och vis ta foten av pedalen och inte bara hoppas på att en utvecklare har säkerhet i åtanke, eftersom systemet(så länge det funkar) upprätthåller policyn. På så vis möjliggör det väl även att man kan arbeta med och utveckla projekt på en större skala.

Använda verktyg:

Docker  
Trivy  
Kubernetes  
Claude  
Gatekeeper – OPA-based policy controller  
