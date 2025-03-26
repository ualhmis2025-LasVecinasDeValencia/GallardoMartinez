---
layout: post
title: "Formulario"
date: 2025-03-19
categories: blog
---

<style>
  .form-container {
    max-width: 500px;
    margin: 2rem auto;
    padding: 2rem;
    background: #f9f5f0;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    font-family: sans-serif;
  }

  .form-container h2 {
    text-align: center;
    color: #7A643F;
    margin-bottom: 1.5rem;
  }

  .form-container label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: bold;
    color: #333;
  }

  .form-container input,
  .form-container textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 8px;
    margin-bottom: 1rem;
    font-size: 1rem;
  }

  .form-container button {
    background-color: #7A643F;
    color: white;
    border: none;
    padding: 12px 20px;
    border-radius: 8px;
    cursor: pointer;
    width: 100%;
    font-size: 1rem;
  }

  .form-container button:hover {
    background-color: #DEBF8B;
  }
</style>

<div class="form-container">
  <h2>📬 Contáctanos</h2>
  <form action="https://formspree.io/f/xeoazdeb" method="POST">
    <label for="email">Tu correo electrónico:</label>
    <input type="email" id="email" name="email" required>

    <label for="message">Tu mensaje:</label>
    <textarea id="message" name="message" rows="5" required></textarea>

    <button type="submit">Enviar</button>
  </form>
</div>
