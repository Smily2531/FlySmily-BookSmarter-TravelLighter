# 🖼️ FlySmily - Visual Showcase & Preview

A comprehensive guide to the **FlySmily** platform's visual identity, features, and user journey.

---

## 🏗️ Landing Page Overview
The landing page provides a clean and modern entry point for travelers. Featuring a powerful search engine, it allows users to find the best flights with ease.

![FlySmily Landing Page Preview](Project%20files/client/src/assets/HomeBg.png)

### Key Highlights:
- **Instant Search**: Real-time filtering by origin and destination.
- **Trip Types**: Toggle between one-way and return journeys.
- **Date Management**: Integrated calendar for journey and return dates.
- **Flight Cards**: Clean display of flight names, IDs, times, prices, and availability.

---

## 🔐 Authentication & Roles
Secure access for three distinct user roles, each with tailored dashboards and features.

- **Customer Login**: Simple and secure registration for travelers.
- **Admin Dashboard**: Centralized control over flights and users.
- **Operator Portal**: Dedicated space for flight status updates and manifest management.

---

## 📊 Feature Visuals & Highlights

### ✈️ Flight Management
Admins can easily add and update flight information.
- **Real-time Updates**: Changes reflect immediately across the platform.
- **Seat Availability Tracking**: Automatic seat counting and booking management.

### 📅 Booking System
- **Seat Classification**: Choose between Economy, Premium Economy, Business, and First Class.
- **Dynamic Pricing**: Base prices adjust according to selected travel class.
- **Ticket Generation**: Automated seat code assignment (e.g., E-1, B-5).

---

## 📽️ Video Demonstration
📺 **[Click here to watch the full project walkthrough](https://drive.google.com/file/d/1_A2jGVhcZXmjomic0ts-w1IdkbxrvQwL/view?usp=sharing)**

---

## 🎨 Design Assets
- **Logo & Branding**: Modern and minimalist airline branding.
- **Iconography**: Intuitive icons for flight types, status, and navigation.
- **Responsive Layout**: Designed to work seamlessly across desktops, tablets, and smartphones.

---

## 🛠️ How to Generate a GIF Preview
If you want to add an animated preview (GIF) to your GitHub repository, you can use the provided `Video Demo/Project Demo.mp4` and convert it using a tool like **[EZGif](https://ezgif.com/video-to-gif)** or **FFmpeg**.

Example FFmpeg command to create a 5-second preview:
```bash
ffmpeg -ss 00:00:03 -t 5 -i "Video Demo/Project Demo.mp4" -vf "fps=10,scale=800:-1:flags=lanczos" demo_preview.gif
```
