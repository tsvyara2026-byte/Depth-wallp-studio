# DEPTH WALLPAPER STUDIO – Android પ્રોજેક્ટ

## શું મળે છે
- Android Studio માટેનું મૂળ project
- Gallery માંથી ફોટો પસંદ કરવો
- ML Kit Selfie Segmentation વડે subject cut-out
- Clock font, colour, size અને position controls
- Depth illusion preview અને PNG save

## APK કેવી રીતે બનાવવો
1. Android Studio (Hedgehog અથવા નવી આવૃત્તિ) ઇન્સ્ટોલ કરો.
2. આ ZIP extract કરીને Android Studio માં `DepthWallpaperStudio` folder ખોલો.
3. Gradle sync પૂર્ણ થવા દો (Internet જરૂરી છે; ML Kit dependency ડાઉનલોડ થશે).
4. Android ફોનમાં USB debugging ચાલુ કરીને Run દબાવો.
5. APK માટે Build > Build Bundle(s) / APK(s) > Build APK(s).

## નોંધ
આ પ્રથમ કાર્યરત આધાર આવૃત્તિ છે; અહીંથી આગળ editor ને વધુ સમૃદ્ધ બનાવી શકાય છે.
ML Kit Selfie Segmentation મુખ્યત્વે વ્યક્તિઓ માટે છે; દરેક પ્રકારની વસ્તુ/પ્રાણી માટે ચોક્કસ cut-out ની ખાતરી નથી.
ફોનની Lock Screen પર સીધું wallpaper લગાવવાની સુવિધા હજી ઉમેરેલી નથી; હાલ PNG Gallery માં સેવ થાય છે.
Android Studio માં build અને વિવિધ ફોન પર પરીક્ષણ કરવું જરૂરી છે.
