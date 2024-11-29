# Instruccions `advanced`
# Webpack: SASS, Minificació, Autoprefix i Errors

Webpack és un module bundler o empacador de mòduls. En termes senzills, és una eina que s'utilitza per processar i empaquetar recursos del front-end com fitxers JavaScript, CSS, HTML, imatges i altres dependències en un projecte web. Aquest empaquetament genera un o més fitxers optimitzats per al navegador, millorant el rendiment i simplificant la gestió dels recursos.

## Mòduls inclosos
- **css-loader**: Permet importar fitxers CSS directament des de JavaScript.
- **style-loader**: Injecta el CSS processat al document HTML durant el desenvolupament.
- **mini-css-extract-plugin**: Extreu el CSS en fitxers separats durant la compilació per a producció.
- **autoprefixer**: Afegeix prefixos CSS per garantir compatibilitat amb navegadors antics.
- **css-minimizer-webpack-plugin**: Minifica els fitxers CSS per reduir la mida en producció.
- **postcss-loader**: Processa CSS amb plugins com autoprefixer.
- **sass i sass-loader**: Permeten treballar amb fitxers SCSS o Sass.


## Requisits

- **Node.js** i **npm** instal·lats.

## Passos per Configurar el Projecte
1. Ves al directori on vols començar la pràctica
   ex. si la practica que he de fer es la `practica04` aniré per la consola al directori pare `practiques`
   ```bash
   practiques/
      ├── practica01/
      ├── practica02/
      └── practica03/
   ```


1. Dintre del directori `practiques`, clona aquest repositori amb la següent instrucció
   ```bash
   git clone https://github.com/HectorPascualIesCarlesVallbona/projecte-webpack-css
   ```

2. En el directori `practiques` t'ha afegit un nou folder `projecte-webpack-css`. Canvia aquest nom carpeta per el nom de carpeta de la pràctica, per exemple. `practica04`

3. Entra a la carpeta
   ```bash
   cd practica04
   ```

2. Instal·la les dependències:
   ```bash
   npm install
   ```

3. Per compilar el projecte:
   ```bash
   npm run build
   ```

4. Per treballar amb observació automàtica:
   ```bash
   npm run start
   ```

## Estructura del Projecte

- `src/`: Conté els fitxers d'entrada.
  - `index.js`: Punt d'entrada JavaScript.
  - `styles/main.scss`: Fitxer SASS per compilar.
- `dist/`: Contindrà els fitxers generats després de la compilació.

---
