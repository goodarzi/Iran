
| TONE | FREQUENCY in Hz | CADENCE in seconds |
------|------------------|--------------------------------------
| Busy tone                 | 425           | 0.5 on 0.5 off |
| Congestion tone           | 425           | 0.25 on 0.25 off |
| Dial tone                 | 425           | continuous |
| Offering tone, trunk      | 425           | 0.2 on 0.2 off 0.2 on 1.4 off |
| Preemption tone           | 1400          | 3x(0.1 on) 0.1 off |
| Ringing tone              | 425           | 1.0 on 4.0 off |
| Re-order tone             | 425           | 0.25 on 0.25 off |
| Special information tone  | 950/1400/1800 | 3x0.33 on 1.0 off |
| Test number tone          | 800           | continuous |
| Call waiting tone         | 425           | 0.2 on 0.2 off 0.2 on 10.0 off |

[indications.conf](indications.conf) contains Iran dial tones implementation for Asterisk.


Reference: http://www.itu.int/ITU-T/inr/forms/files/tones-0203.pdf
