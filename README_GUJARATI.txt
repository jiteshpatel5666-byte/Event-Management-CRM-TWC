EVENT MANAGEMENT CRM – APK બનાવવાની સરળ રીત (Android Studio વગર)

આ ZIP માં Android app નો source project અને GitHub Actions દ્વારા APK બનાવવાની workflow સામેલ છે.
હાલમાં APK ફાઇલ આ ZIP માં નથી.

APK મેળવવા માટે:
1. GitHub.com પર પોતાનું account બનાવો / sign in કરો.
2. New repository બનાવો (ઉદાહરણ: event-management-crm).
3. આ ZIP extract કરીને અંદરના બધા files અને folders repository માં upload કરો. .github folder પણ upload કરવો જરૂરી છે.
4. Repository માં Actions tab ખોલો અને “Build Android APK” workflow પસંદ કરો.
5. “Run workflow” દબાવો. Build સફળ થાય પછી workflow run ખોલો.
6. નીચે Artifacts માં “Event-Management-CRM-APK” download કરો અને ZIP extract કરો.
7. app-debug.apk તમારા Android phone માં મોકલો અને install કરો. ફોન પૂછે તો આ source માંથી app install કરવાની permission આપો.

નોંધ:
- આ રીતમાં Android Studio જરૂરી નથી, પરંતુ GitHub account અને internet જરૂરી છે.
- આ debug APK છે, Play Store માટે signed release નથી.
- App નો હાલનો ડેટા તે જ ફોનમાં local રાખવામાં આવે છે. ફોન બદલતા અથવા app data clear કરતા પહેલાં backup/export જરૂરી છે.
- Excel ના 161 event records પહેલેથી સામેલ છે. Customer, mobile, advance અને payment details મૂળ Excel માં નહોતા એટલે ખાલી છે.
- Pending = Price - Advance (શૂન્યથી ઓછું નહીં), app માં auto ગણાશે.
