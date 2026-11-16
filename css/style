:root {
  --bg: #f5f7fa;
  --text: #1b2430;
  --card-bg: #ffffff;
  --accent: #0a7c8c;
  --border: #d5dbe3;
}

body.dark {
  --bg: #121820;
  --text: #e8edf3;
  --card-bg: #1d2630;
  --accent: #4cc3d3;
  --border: #33414f;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
  background: var(--bg);
  color: var(--text);
  line-height: 1.6;
}

header, main, footer {
  max-width: 900px;
  margin: 0 auto;
  padding: 20px;
}

h1 {
  margin: 0 0 16px;
}

.bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 16px;
  border: 1px solid var(--border);
  background: var(--card-bg);
}

.bar-name {
  font-weight: bold;
}

.bar-links a {
  margin-left: 16px;
  color: var(--accent);
  text-decoration: none;
}

.bar-links a:hover {
  text-decoration: underline;
}

.photo {
  display: block;
  width: 220px;
  height: 220px;
  object-fit: cover;
  border-radius: 50%;
  margin: 0 auto 24px;
  border: 3px solid var(--accent);
}

.cards {
  display: flex;
  gap: 16px;
}

.card {
  flex: 1;
  padding: 16px;
  background: var(--card-bg);
  border: 1px solid var(--border);
  border-radius: 8px;
}

.card h2 {
  margin-top: 0;
  color: var(--accent);
}

#contact {
  margin-top: 32px;
}

form {
  display: flex;
  flex-direction: column;
  max-width: 400px;
}

label {
  margin-top: 12px;
  font-weight: bold;
}

input {
  padding: 8px;
  margin-top: 4px;
  border: 1px solid var(--border);
  border-radius: 4px;
  background: var(--card-bg);
  color: var(--text);
  font-size: 1rem;
}

button {
  margin-top: 32px;
  padding: 10px 20px;
  border: none;
  border-radius: 4px;
  background: var(--accent);
  color: var(--bg);
  font-size: 1rem;
  cursor: pointer;
}

footer {
  text-align: center;
  border-top: 1px solid var(--border);
  margin-top: 32px;
}

@media (max-width: 600px) {
  .cards {
    flex-direction: column;
  }
}
