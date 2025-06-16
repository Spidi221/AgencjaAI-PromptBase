# 🎯 Prompt: Umawianie wizyty przez VoiceAgenta AI

**Cel:**  
Zarezerwować wizytę u dentysty na podstawie danych pacjenta.

**Kontekst systemowy:**  
- Gabinet stomatologiczny, godziny otwarcia: 12–20  
- Integracja z Google Calendar  
- VoiceAgent działa przez Twilio i ElevenLabs

**Prompt:**  
„Dzień dobry! Chciałbym umówić się na wizytę do dentysty na czwartek po godzinie 15:00. Mam na imię Jan Kowalski, mój numer to 666444333.”

**Komentarze:**  
- 🟢 Działa z GPT-4 i Claude 3  
- 🔴 Claude lepiej obsługuje niedopowiedzenia  
- ✏️ Można dodać fallback na „czy chcesz potwierdzenie SMS?”
