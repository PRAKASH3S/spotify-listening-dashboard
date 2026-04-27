<div align="center">

<img src="https://img.shields.io/badge/Spotify-1DB954?style=for-the-badge&logo=spotify&logoColor=white" />
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />

# 🎵 Spotify Listening History — Dashboard & Analysis

### _Uncovering 10+ years of music listening habits through data_

</div>

---

## 📊 Live Dashboard

> **[👉 Click here to view the interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjA0YmE5YmMtZmQxMy00ZDY2LWJmMTgtZWE3NjcwMjM2MGE4IiwidCI6IjcwZGUxOTkyLTA3YzYtNDgwZi1hMzE4LWExYWZjYmEwMzk4MyIsImMiOjN9&embedImagePlaceholder=true)**

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `spotify_history.csv` | Raw Spotify extended streaming history (2013–2024) |
| `README.md` | Project documentation |

---

## 🔍 Project Overview

This project analyzes **10+ years of personal Spotify streaming history** exported via Spotify's "Request Your Data" feature. The dataset contains **149,860 plays** across a wide range of artists, albums, and platforms — from 2013 to 2024.

The goal is to surface meaningful listening patterns, top artists, behavioral habits (time-of-day, day-of-week), and platform usage trends using **Power BI** for visual storytelling.

---

## 📈 Key Insights

| Metric | Value |
|--------|-------|
| 🎵 Total Plays | 149,860 |
| ⏱️ Total Hours Listened | 5,341.5 hrs |
| 🎤 Unique Artists | 4,113 |
| 🎶 Unique Tracks | 13,839 |
| ⏭️ Skip Rate | 5.3% |
| 📅 Date Range | Jul 2013 – 2024 |

### 🏆 Top Artists by Plays

| Rank | Artist | Plays |
|------|--------|-------|
| 1 | The Beatles | 13,621 |
| 2 | The Killers | 6,878 |
| 3 | John Mayer | 4,855 |
| 4 | Bob Dylan | 3,814 |
| 5 | Paul McCartney | 2,697 |

### 🕐 Listening Behavior
- **Peak listening hours:** Late night (10 PM – 2 AM)
- **Busiest day:** Sunday
- **Most-used platform:** Android (93% of plays)
- **Peak listening year:** 2020 (~920 hours)

---

## 🗃️ Dataset Description

The raw data (`spotify_history.csv`) is exported directly from Spotify's privacy portal and contains the following fields:

| Column | Description |
|--------|-------------|
| `spotify_track_uri` | Unique Spotify URI for the track |
| `ts` | Timestamp of when the track was played |
| `platform` | Device/platform used (Android, iOS, web player, etc.) |
| `ms_played` | Milliseconds the track was played |
| `track_name` | Name of the track |
| `artist_name` | Artist name |
| `album_name` | Album name |
| `reason_start` | Why the track started (e.g., clickrow, autoplay) |
| `reason_end` | Why the track ended (e.g., trackdone, skipped) |
| `shuffle` | Whether shuffle was on |
| `skipped` | Whether the track was skipped |

---

## 🛠️ Tools & Technologies

- **Power BI** — Interactive dashboard and visual analytics
- **Python (pandas)** — Data cleaning and preprocessing
- **Microsoft Excel** — Exploratory analysis
- **GitHub** — Version control and project hosting

---

## 🚀 How to Use

1. **View Dashboard** — Open the [Power BI link](https://app.powerbi.com/view?r=eyJrIjoiYjA0YmE5YmMtZmQxMy00ZDY2LWJmMTgtZWE3NjcwMjM2MGE4IiwidCI6IjcwZGUxOTkyLTA3YzYtNDgwZi1hMzE4LWExYWZjYmEwMzk4MyIsImMiOjN9&embedImagePlaceholder=true) in any browser — no login required
2. **Explore the Data** — Download `spotify_history.csv` from this repo
3. **Reproduce the Analysis** — Load the CSV into Python/Excel/Power BI with the column reference above

---

## 👤 About

**Prakash Teki** — Business Analytics Graduate | Data Analyst

[![GitHub](https://img.shields.io/badge/GitHub-PRAKASH3S-181717?style=flat&logo=github)](https://github.com/PRAKASH3S)
[![Portfolio](https://img.shields.io/badge/Portfolio-prakash3s.github.io-0f9d58?style=flat&logo=google-chrome&logoColor=white)](https://prakash3s.github.io)

---

<div align="center">
  <sub>Data exported from Spotify via the Personal Data Request feature. For personal/portfolio use only.</sub>
</div>
