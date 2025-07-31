# Smart Image Cropper - Frontend Coding Challenge

## Overview

Build a modern, interactive web application that allows users to upload images and generate optimized crops for various social media platforms using AI-powered suggestions.

![Just keep smiling](./Screenshot.png)

## Challenge Description

Create a Vue.js application that demonstrates your skills in:

- Modern frontend frameworks (Vue 3 Composition API)
- Responsive UI/UX design
- API integration
- State management
- Component architecture

## Core Requirements

### 1. Image Upload System

- **File Upload Interface**: Implement functionality using **Uploadcare**
- **Multiple Format Support**: Accept common image formats (JPEG, PNG, WebP)
- **Preview Gallery**: Display uploaded images in a responsive grid

### 2. Social Media Preview Generator

- **Platform Support**: Generate crops for major platforms (Instagram, Facebook, Twitter, LinkedIn, etc.)
- **Aspect Ratio Handling**: Automatic cropping based on platform requirements
- **Preview Grid**: Display all generated previews in an organized layout
- **Download Functionality**: Individual and bulk download options

## Technical Specifications

### Frontend Stack

- **Framework**: Vue 3 with Composition API
- **Build Tool**: Vite
- **Styling**: SCSS with CSS custom properties
- **Image Processing**: Uploadcare for upload and transformations
- **State Management**: Vue 3 reactive system

### Key Features to Implement

#### Required Components

1. **FileUploader Component**

   - Upload progress indicators
   - Theme-aware styling

2. **SocialMediaPreviews Component**
   - Grid layout for multiple platform previews
   - Platform-specific branding and colors
   - Download buttons with hover effects
   - Responsive design for mobile devices

### API Integration

- **Image Processing**: Use Uploadcare or similar service for image manipulation
- **Smart Cropping**: Use Uploadcare for smart crop suggestions
- **Format Optimization**: Generate platform-specific image formats

### Vue.js Mastery Tests 🎯

- **Composition API**: Use `<script setup>` syntax with advanced composables
- **🔥 VUE CHALLENGE**: Create custom `useImageProcessor` composable with reactive transforms

### Technical Improvements

- **TypeScript Integration**: Type safety throughout the application

## Time Allocation

### Recommended Timeline (6-8 hours)

- **Setup & Architecture** (30 minutes)
- **Core Components** (2-3 hours)
- **Styling & Theming** (1-2 hours)
- **Integration & Testing** (1 hour)
- **Polish & Documentation** (1 hour)

## Submission Requirements

### Deliverables

1. **Source Code**: Complete Vue.js application
2. **README.md**: Setup instructions and feature documentation
3. **Live Demo**: Deployed application (Netlify, Vercel, etc.) (Optional)
4. **Code Walkthrough**: Brief explanation of key architectural decisions

### Documentation Should Include

- Installation and setup instructions
- Feature overview with screenshots
- Technical decisions and trade-offs
- Known limitations or areas for improvement (Optional)
- Future enhancement ideas (Optional)

## Getting Started

### Initial Setup

```bash
# Create new Vue project
npm create vue@latest smart-image-cropper
cd smart-image-cropper
npm install

# Add required dependencies
npm install @uploadcare/file-uploader

# Note: Use Uploadcare as the primary image upload solution
# This provides professional-grade image handling, automatic format
# optimization, and built-in image transformations

# Start development server
npm run dev
```

## Resources

### Documentation

- [Vue 3 Composition API](https://vuejs.org/guide/extras/composition-api-faq.html)
- [Uploadcare File Uploader](https://uploadcare.com/docs/file-uploader/)
- [CSS Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)
- [Smart Crop Operations - Uploadcare](https://uploadcare.com/docs/transformations/image/resize-crop/#operation-smart-crop)

**Good luck! We're excited to see your creative and technical approach to this challenge.**
