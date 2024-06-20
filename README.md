# my-react-tailwind-app

import React from 'react';
import './App.css'; // Update this with Tailwind styles
import ProfilePic from '![priscilla jpg](https://github.com/25Priscilla/my-react-tailwind-app/assets/155515052/9b13e3a3-3b48-4aee-af00-7cbf6b356c36)'; 

function App() {
  return (
    <div className="container mx-auto p-4">
      <header className="text-center mb-4">
        <img src={ProfilePic} alt="Profile" className="rounded-full h-40 w-40 mx-auto mb-4" />
        <h1 className="text-3xl font-bold">Priscilla Rachel Toby</h1>
        <p className="text-lg text-gray-700">Web Developer</p>
      </header>
      <section className="mb-8">
        <h2 className="text-xl font-bold mb-2">Contact Information</h2>
        <ul className="text-lg">
          <li>Email: 8147202256.com</li>
          <li>Phone: 8147202256</li>
        </ul>
      </section>
      <footer className="text-center text-gray-500 text-sm">
        &copy; 2024 Priscilla Rachel Toby. All rights reserved.
      </footer>
    </div>
  );
}
