🎀 My Portfolio Website

An interactive personal portfolio web application built with Streamlit. This project is designed to showcase personal information, projects, and contact details in a clean, modern, and visually appealing interface.

It serves as a digital resume, allowing visitors to quickly learn about the developer, explore work, and get in touch.

📖 Features

🎨 Modern UI Design – Styled using custom CSS, Google Fonts, and a minimalist layout for a sleek user experience.

👋 Hero Section – Displays a bold introduction with name, role, and a short personal description.

🧭 Navigation Buttons – Interactive buttons for easy page switching:

View My Work → Projects page
Get in Touch → Contact page

📂 Multi-Page Support – Organized structure with separate pages (projects.py, contact.py).

📱 Responsive Layout – Built with Streamlit columns for proper alignment across screen sizes.

⚡ Interactive Elements – Buttons and layout designed for smooth user interaction.

🦶 Footer Section – Includes personal details like name, role, year, and location.

🛠️ Technologies Used
Python – Core programming language
Streamlit – Web app framework
HTML (via Markdown) – Structure and layout customization
CSS – Styling (fonts, colors, spacing, UI enhancements)
Google Fonts – Typography (Playfair Display, DM Sans)
🚀 How to Use

Run the application locally:

 [Click here to view my portfolio](https://pulseproi.github.io/Multipage_Porfolioapp/)

pip install streamlit
streamlit run app.py

Then open the app in your browser.

⚙️ Customization

You can easily personalize the portfolio:

✏️ Edit Content – Update text (name, description, footer) inside app.py

🎨 Modify Design – Adjust styles inside the st.markdown() CSS block

🔗 Update Navigation – Link buttons to other pages or add new ones

📁 Add Pages – Create new .py files for additional sections

💡 Use Case
Students building their first portfolio
Developers showcasing projects for internships/jobs
Anyone wanting a simple and elegant digital resume
📄 Notes

If navigation doesn’t work, replace:

st.switch("projects.py")

with:

st.switch_page("projects.py")
Ensure all pages are in the same directory.
📍 Author

Rena Valenzuela
Computer Science Student · Masbate, Philippines
