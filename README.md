# Smart Home Blueprint
> [!NOTE]  
> Treść będzie się pojawiać stopniowo, obserwuj żeby być na bieżąco.

## 1. Sterowanie światłem
### Założenia
* sterowanie włącznikami ściennymi oraz przez Home Assistant (HA)
* w razie awarii serwera na którym działa HA, włączniki ścienne nadal działają i są niezależne od sterowania przez HA
* HA zna stan poszczególnych obwodów oświetleniowych i monitoruje ich stan na bieżąco nawet jeśli dany obwód został włączony/wyłączony przez włącznik ścienny
* wszystkie włączniki ścienne są monostabilne (wysyłają krótki impuls do przekażnika)
* instalacja przewodowa
* instalacja oparta jest na ogólnodostępnych produktach i standardach, nie bazuje na żadnym z zamkniętych standardów smart home typu np. KNX
* instalacja jest łatwa do zrozumienia i implementacji przez każdego elektryka z uprawnieniami

### Komponenty
#### Przekażnik "smart"
* Waveshare 8-ch Ethernet Relay Module (B) https://www.waveshare.com/modbus-poe-eth-relay-b.htm.htm

<img src="https://github.com/user-attachments/assets/ae9b15bd-2039-4ea9-bd94-343c48a9d258" width="250">

<img src="https://github.com/user-attachments/assets/66782516-afbd-41e7-bb3e-639bfa5041f6" width="250">

<img src="https://github.com/user-attachments/assets/fa244f65-2659-4a2d-bebc-baeab10731ef" width="250">





#### Przekaźnik "zwykły"
* RelPol RPB-2ZSMI-UNI https://www.relpol.pl/en/Products/Bistable-impulse-relays/Bistable-relay-RPB-2ZSMI-UNI


