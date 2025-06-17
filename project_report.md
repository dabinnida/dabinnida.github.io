# Project Report: Busan Pet Adoption Website

## 1. Project Overview

This website was created to support the adoption of stray animals in **Busan, South Korea**.  
The **target users** are Busan citizens who are interested in adopting pets.  
The site is designed to help them easily find, explore, and save potential animals for adoption.

### Key Features
- Animal selection cards (dog/cat)
- Detailed pages for each animal (including personality, traits, and location)
- Breed filtering and search function
- Add to favorites and view favorites list
- Personality-based filter buttons (3 types)
- Check location through an interactive map (KakaoMap)
- Filter to show only animals currently available for adoption
- Translation feature for accessibility

---

## 2. Tools and Libraries Used

- **HTML, CSS, JavaScript**: for frontend development
- **GitHub Pages**: for static website hosting
- **KakaoMap API**: for location-based map integration (via external window)
- **Pixabay**: for free animal images by breed
- **www.animal.go.kr**: official government site from which real stray animal data was collected and processed

---

## 3. What Was Tried and Succeeded

- Collected real stray animal data from the Korean government site and **organized it into Excel** (including traits, personality, and location) for use on the site
- Initially attempted to embed the map inside the website but encountered issues; successfully implemented **external KakaoMap window**
- Used **free breed images from Pixabay**, assigning them randomly to each card as substitutes for actual photos
- Attempted a dynamic personality filter (like the breed filter), but due to recurring errors, simplified it to **three personality buttons**

---

## 4. What Was Difficult or Failed

- **Embedding KakaoMap within the site** was difficult due to JavaScript integration issues, so an external window approach was used instead
- **Failed to implement downloadable adoption form**
- Could not create a multi-select dynamic **personality filter** due to persistent bugs, so replaced with simple buttons
- Actual photos of the listed animals could not be used due to access limitations, so Pixabay images were used instead

---

## 5. Future Improvements

- Improve the **filter button UI/UX** to make selection more intuitive
- Implement **adoption application download feature**
- Reattempt **embedding the map directly** into the site using iframe or better JS methods
- I would like to activate a region-based filter and expand the website's coverage beyond Busan to include all regions across South Korea.

---

## 6. References

- [Korean Animal Protection Information System (animal.go.kr)](https://www.animal.go.kr)
- [Pixabay Free Images](https://pixabay.com/)
- [KakaoMap API](https://apis.map.kakao.com/)
