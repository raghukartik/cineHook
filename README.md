
# 🍿cineHook
> *Your personal movie rating & watchlist app*

**cineHook** is a React-based movie watchlist app that lets you search movies, rate them out of 10, and add them to your watched list. Your data is saved locally in your browser using **local storage**, so it persists even after refreshing the page.

---

## ✨ Features

- 🔍 Search for movies using the **OMDb API**
- ⭐ Rate movies out of 10
- ➕ Add movies to your **Watched List**
- 💾 Data saved using **Local Storage**
- 🖥️ Simple, responsive UI built with **React** and **plain CSS**

---

## 📸 Demo

*https://cine-hook.vercel.app/*  
[Live Demo](#)

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/cineHook.git
cd cineHook
```

### 2. Install dependencies

```bash
npm install
```

### 3. Add your OMDb API key

Create a `.env` file in the root directory and add:

```env
REACT_APP_OMDB_API_KEY=your_api_key_here
```

> 🔑 You can get a free OMDb API key from [http://www.omdbapi.com/apikey.aspx](http://www.omdbapi.com/apikey.aspx)

### 4. Start the development server

```bash
npm start
```

Visit [http://localhost:3000](http://localhost:3000) to use the app in your browser.

---

## 🛠️ Built With

- [React.js](https://reactjs.org/)
- [OMDb API](http://www.omdbapi.com/)
- Plain HTML & CSS
- JavaScript (ES6+)
- Local Storage API

---

## 📁 Folder Structure

```
cineHook/
├── public/
├── src/
│   ├── App.js          # Main app component
│   ├── index.js        # Entry point
│   └── ...
├── .env                # Environment variables (API key)
├── package.json
└── README.md
```

---

## 🧠 How It Works

1. Search input triggers API call to OMDb API.
2. Search results are shown in real time.
3. Clicking a movie lets you:
   - View details
   - Rate it out of 10
   - Add to your **Watched List**
4. Watched list is stored in `localStorage` and retrieved on app load.

---

## 📌 Future Enhancements

- 🌓 Dark/Light theme toggle
- 🔄 Sync data with backend or cloud
- 📊 Sort/filter watched movies
- 📝 Add notes or reviews for each movie

---

## 🙏 Acknowledgments

- Movie data provided by [OMDb API](http://www.omdbapi.com/)
- Inspired by personal love for movies and the need for a simple watchlist app

