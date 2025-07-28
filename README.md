

# 🗺️ TehranNavigator

A Python-based interactive route planner for **Tehran, Iran**, using real street network data. This project allows users to input origin and destination addresses and visualize the shortest path between them on an interactive map.

---

## 🌟 Features

- **Interactive Widgets**: Input origin and destination with ease.
- **Geocoding**: Converts addresses to coordinates using Nominatim.
- **Street Network Data**: Fetches real road data of Tehran via **OSMnx**.
- **Shortest Path Calculation**: Uses **NetworkX** to compute the optimal route.
- **Visualization**: Displays the route interactively using **ipyleaflet**.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.7+
- Jupyter Notebook or JupyterLab

### 📦 Installation

Install required packages using pip:

```bash
pip install osmnx networkx ipyleaflet geopy scikit-learn ipywidgets
```

Enable `ipywidgets` extension (if not already):

```bash
jupyter nbextension enable --py widgetsnbextension
```

---

## ▶️ Usage

Run the notebook containing the code, and you'll see:

- Two input fields for **Origin** and **Destination**
- A **"Show Route"** button
- An interactive map displaying the computed route

### Example Input

- **Origin**: `Tehran University, Tehran`
- **Destination**: `Azadi Tower, Tehran`

Click **Show Route** to visualize the path!

---

## 🧠 How It Works

1. **Geocode Addresses**: Converts user input into latitude/longitude.
2. **Fetch Graph Data**: Downloads the street network of Tehran.
3. **Find Nodes**: Locates nearest nodes on the graph to start/end points.
4. **Compute Path**: Calculates the shortest path using Dijkstra’s algorithm.
5. **Visualize**: Draws the path on an interactive map with markers.

---

## 🧰 Technologies Used

| Tool         | Purpose                          |
|--------------|----------------------------------|
| **OSMnx**    | Fetching OpenStreetMap data      |
| **NetworkX** | Graph analysis and pathfinding   |
| **ipyleaflet** | Interactive mapping in Jupyter |
| **geopy**    | Geocoding addresses              |
| **ipywidgets** | UI controls in notebooks       |

---

## 📷 Preview

> _Example of route visualization from Tehran University to Sharif University_

![Tehran Route Visualization](./data/Screenshot%202025-07-28%20003048.png) <!-- Optional image -->

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## 💡 Future Improvements

- Support for multiple cities
- Real-time traffic integration
- Saving/exporting routes as GPX/JSON
- Mobile-friendly interface

---

## 👨‍💻 Author

**Your Name**  
[GitHub Profile](https://github.com/Amir-Hossein-shamsi)  
📧 shamsiamirhossein1@gmail.com

---

## ⭐️ Show Your Support

If you like this project, give it a ⭐️ on [GitHub](https://github.com/Amir-Hossein-shamsi/TehranNavigator)!
