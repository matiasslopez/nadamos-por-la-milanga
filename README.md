# Nadamos por la Milanga

Jueguito pixel art de natación para el grupo de la pileta. Elegís nadador (Pablito, Luis, Facu, Mati, Andre o Mica), esquivás lentos, señoras y al que nada por la suya, y el premio es una milanesa a la napolitana.

- Juego: `index.html` (un solo archivo, sin build).
- Ranking y contador de visitas: Firebase Firestore. La configuración va en `FIREBASE_CONFIG` dentro de `index.html`.
- Reglas de seguridad de la base: `firestore.rules` (pegarlas en Firebase → Firestore → Reglas).
- Contador de visitas: abrir el juego una vez con `?admin=milanga-admin` al final del link.
