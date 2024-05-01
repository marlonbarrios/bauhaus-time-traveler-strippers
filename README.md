
# the bauhaus time traveler are Strippers


## About the Project

**Duets in Latent Space** is an application developed by Marlon Barrios Solano, showcasing a blend of concept, programming, generative AI, sound design, and performance. It was brought to life during an artistic and research residency at Lake Studios Berlin in February 2024.


### Composition

The project is an amalgamation of various elements including software development, a real-time text to image gerative AI space for performance as a live app that runs in the browser, a sound space crafted with Musicgen, and a drawing tool. Additionally, users/performer can immerse themselves in the experience by playing the soundtrack created specifically for the app. 

Latent space refers to a conceptual and mathematical space generated by algorithms, particularly those used in machine learning and generative models. This space is characterized by the high-dimensional representation of data where similar data points are mapped closely together, and dissimilar points are further apart. In essence, latent spaces serve as the underlying structure that models use to understand and generate new data instances based on learned patterns, without being explicitly programmed with specific rules for every possible outcome.

The intention to perform actions in latent space, especially with a model, is to perform within an unknown probability space, utilizing the generative capabilities of the model to create art or perform in real-time. This process involves interacting with the model in a way that it generates outputs based on the vast, unseen dimensions of the data it has learned from, yet doing so in a manner that is unpredictable and unique to each performance. The performer, by manipulating inputs (prompts) or guiding the model's generative process, improvises with these outputs, creating an interplay between the expected and the unexpected, the known and the unknown. This act of performing in real-time within latent space becomes a dance (or a drawing) within a probability space.

The notion of Bauhaus artists as embodiments of time travelers captures my imagination, painting them as navigators through speculative futures, escaping persecution, and finding solace in the purity of abstraction and geometry. In my fantasy, these "Bauhaus Time Travelers" move with speed and beauty, their journey a harmonious blend of geometries and fluidity, experimentation, and design. I envision them transcending the constraints of their era, embodying diverse genders, ethnicities, and ages, challenging the prevalent whiteness of the art world. This dream, rich with the potential of what could be, reimagines the Bauhaus legacy as a multidimensional space, vibrant with inclusivity, humor and the boundless exploration of form and function across time.


## Deployment

It can be an installation, a webpage, a live performance and/or an online lecture/performance.

### Features

- **LCM Turbo:** Leveraging the power of Fal.ai for (almost) real-time, instant image from webcam guided by text-to-image conversion.
- **Soundtrack:** A specially composed soundtrack that users can play, enhancing the visual experience with a complementary sound space | created with AI Musicgen model.
- **Innovative Design:** Drawing inspiration from the Bauhaus movement with ideas of time travel.
- **Sound Design & Performance:** Marlon Barrios Solano integrates sound landscapes and performance space in front of laptop.


## Explore More

- **Live Application:** Experience the Bauhaus Time Traveler in action [here](https://bauhaus-time-traveler.vercel.app/).
- **Marlon Barrios Solano:** For more about Marlon, his projects, and how you can support his work, visit his [Linktree](https://linktr.ee/marlonbarriososolano).


## Getting Started with LCM Turbo

LCM Turbo allows you to transform the camera input guided by the text text into visuals instantly. Follow these steps to set up and start using the app.

### Prerequisites

Node.js is required to run the application and manage its dependencies.

### Installation Guide

1. **Clone the Repository**

   Get started by cloning the repository to your local system.

   ```sh
   git clone <repository-url>
   ```

2. **Install Dependencies**

   Enter the project directory and install necessary dependencies.

   ```sh
   cd <project-directory>
   npm install
   ```

3. **Configure Environment**

   Rename `.env.local.example` to `.env.local` and input your Fal.ai API Key. You can get your API key from the [Fal.ai Dashboard](https://www.fal.ai/dashboard/keys).

   ```plaintext
   # .env.local contents example
   FAL_AI_API_KEY=your_api_key_here
   ```

4. **Run the Application**

   With everything set up, launch the application.

   ```sh
   npm run dev
   ```

   Open `http://localhost:3000` in your browser to see the app in action.



## MIT License

Copyright (c) 2024 Marlon Barrios Solano

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
