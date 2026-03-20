
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', Arial, sans-serif;
  background: linear-gradient(135deg, #fff0f5, #fff5f8);
  color: #1a1a1a;
  line-height: 1.6;
  padding: 60px 20px;
  text-align: center;
  transition: background 0.5s;
}

header,
main {
  max-width: 900px;
  margin: 0 auto;
}

section {
  margin-top: 70px;
  max-width: 620px;
  margin-left: auto;
  margin-right: auto;
  transition: transform 0.3s;
}

section:hover {
  transform: translateY(-3px);
}

h1, h2, h3, p {
  font-family: 'Inter', Arial, sans-serif;
}

h1 {
  font-size: 3rem;
  color: #b03a5b;
  text-shadow: 1px 1px 2px #f6c1cf;
  transition: color 0.3s;
}

h1:hover {
  color: #ff6699;
}

h2 {
  font-size: 1.6rem;
  margin-bottom: 24px;
  color: #8f2f4a;
  text-transform: uppercase;
  letter-spacing: 1px;
}

h3 {
  font-size: 1.1rem;
  margin-top: 18px;
  color: #7a2a45;
}

p {
  color: #333;
  margin: 0 auto;
  font-weight: 400;
}

.intro {
  margin-bottom: 40px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
}

.intro img {
  width: 340px;
  height: 340px;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid #f6c1cf;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  transition: transform 0.3s, box-shadow 0.3s;
}

.intro img:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}

.tagline {
  font-size: 1.2rem;
  color: #6b2a3c;
  font-weight: 500;
}

.interests ul {
  list-style: none;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 14px;
  margin: 10px auto 0;
  max-width: 620px;
  justify-items: center;
}

.interests li {
  background-color: #fde3ea;
  padding: 14px 18px;
  border-radius: 50px;
  text-align: center;
  font-size: 0.95rem;
  font-weight: 500;
  cursor: pointer;
  transition: transform 0.3s, background 0.3s, box-shadow 0.3s;
}

.interests li:hover {
  transform: scale(1.1);
  background-color: #ffccd9;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.work {
  margin-top: 80px;
}

.project {
  max-width: 620px;
  margin: 0 auto 80px;
  text-align: center;
  transition: transform 0.3s;
}

.project:hover {
  transform: translateY(-5px);
}

.project-img {
  width: 560px;
  height: 400px;
  object-fit: cover;
  border-radius: 12px;
  box-shadow: 0 6px 15px rgba(0,0,0,0.1);
  transition: transform 0.3s, box-shadow 0.3s;
}

.project-img:hover {
  transform: scale(1.02);
  box-shadow: 0 10px 25px rgba(0,0,0,0.15);
}

.work .project:nth-of-type(2) .project-img {
  width: 450px;
  height: 550px;
}

.project p {
  margin: 12px auto 0;
  max-width: 520px;
  color: #444;
}

.influences {
  margin-top: 80px;
}

.influences p {
  font-style: italic;
  color: #5a2a37;
  max-width: 600px;
  margin: 0 auto;
}

footer {
  margin-top: 100px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 8px;
}

.contact {
  font-size: 0.85rem;
  color: #6b2a3c;
}

a {
  color: #b03a5b;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s;
}

a:hover {
  color: #ff6699;
  text-decoration: underline;
}

@media (max-width: 600px) {
  .intro img {
    width: 300px;
    height: 300px;
  }

  .project-img {
    width: 90%;
    height: auto;
  }
}
