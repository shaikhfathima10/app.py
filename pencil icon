# pencil icon 
import streamlit as st

st.set_page_config(page_title="AI Career Assistant", page_icon="🎯")

st.title("🎯 AI-Powered Career Assistant")
st.write("Welcome! Get personalized career guidance based on your skills and goals.")

# Input
user_input = st.text_input("👉 Enter your skills or career goals:")

# Button + Output
if st.button("Get Career Advice"):
    if user_input:
        st.subheader("🔍 Suggested Career Paths:")
        if "python" in user_input.lower():
            st.write("- Data Scientist")
            st.write("- Backend Developer")
            st.write("- AI Engineer")
        elif "design" in user_input.lower():
            st.write("- UI/UX Designer")
            st.write("- Graphic Designer")
            st.write("- Product Designer")
        else:
            st.write("- Software Developer")
            st.write("- Analyst")
            st.write("- Project Coordinator")

        st.subheader("📘 Next Steps:")
        st.write("1. Learn advanced topics in your field")
        st.write("2. Build projects to showcase your skills")
        st.write("3. Apply for internships for real-world experience")
    else:
        st.warning("⚠ Please enter your skills first!")
