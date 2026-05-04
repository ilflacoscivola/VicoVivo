# Mappa Illustrata Genova

## Documentation

### Project Overview
Mappa Illustrata Genova is a project aimed at creating an interactive illustrated map of the city of Genoa, showcasing points of interest (POIs) including historical sites, cultural venues, and local attractions.

### Setup Instructions
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/ilflacoscivola/VicoVivo.git
   cd VicoVivo
   ```
2. **Install Dependencies**:
   Make sure you have Node.js and npm installed. Then run:
   ```sh
   npm install
   ```
3. **Run the Project**:
   To start the development server:
   ```sh
   npm start
   ```
   Navigate to `http://localhost:3000` in your browser.

### Project Structure
- **/src**: Contains the main source code.
- **/public**: Contains static files such as images and index.html.
- **/data**: Contains data files for POIs and other resources.

### Adding Points of Interest (POIs)
1. **Locate the Data File**:
   Find the relevant data file in the `/data` directory that corresponds to the type of POI you want to add.
2. **Edit the File**:
   Use a text editor to add your new POI in the appropriate format. Each POI should include fields such as name, description, coordinates, and category.
3. **Update the Application**:
   Save the file and restart the development server to see your changes reflected on the map.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.