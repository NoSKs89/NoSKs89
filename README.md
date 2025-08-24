# Stephen Erickson | Full-Stack Developer & 3D Web Experience Creator

<div align="center">
  <img src="profile_image.jpg" alt="Stephen" width="750" style="border-radius: 100px"/>
  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)
</div>

## Creative Technologist | Environmental Advocate | Innovation Driver

I craft immersive digital experiences that blend cutting-edge technology with meaningful storytelling. My work spans interactive 3D environments, full-stack applications, and socially conscious platforms that challenge perspectives and inspire action.

---


<br/>

## Featured Projects (give preview gifs a moment to load)

### GrooveWash - 3D Audio-Visual Record Cleaning Experience
[![GrooveWash Preview](./screenshots/groovewash-preview.gif)](https://groovewash.com)

**Interactive Business Website** | **React 19** | **Three.js** | **Web Audio API** | **Material-UI**

An immersive showcase for professional vinyl record cleaning services:
- **Real-Time Audio Visualization** - WebGL-powered 3D record animations synced to audio
- **Ultrasonic Process Simulation** - Interactive 3D demonstrations of cleaning technology
- **Advanced Post-Processing** - Custom GLSL shaders and particle systems
- **Business Integration** - Contact forms, digital waivers, and service booking
- **SEO-Optimized** - React Helmet integration for search engine visibility

```45:52:groove-polish/src/components/AudioPlayer.js
// Real-time audio-reactive 3D visualization
const { audioData } = useAudioData(audioRef);
const frequencyData = useMemo(() =>
  audioData ? audioData.frequency : new Uint8Array(32),
  [audioData]
);

<Canvas camera={{ position: [0, 0, 5] }}>
  <Record3D frequencyData={frequencyData} />
  <ParticleSystem />
</Canvas>
```


### Wedding WriteBack - Enterprise-Grade Wedding Platform
[![Wedding WriteBack Preview](./screenshots/wedding-writeback-preview.gif)](https://weddingwriteback.com)

**Full-Stack Application** | **React 18** | **AWS Cloud** | **MongoDB** | **TypeScript**

A sophisticated wedding planning platform featuring:
- **Drag-and-Drop Visual Editor** - Intuitive interface for creating personalized wedding experiences
- **3D Interactive Elements** - Immersive parallax effects and dynamic animations
- **Real-Time Collaboration** - Guest management with RSVP tracking and photo sharing
- **Enterprise Security** - AWS Lambda, API Gateway, and comprehensive authentication
- **Mobile-First Design** - Responsive layouts optimized for all devices

```12:15:wedding-write-back/src/components/ExperienceSetupPage/ElementSlot.tsx
// Advanced drag-and-drop system with real-time preview
<DragDropContext onDragEnd={handleDragEnd}>
  <Droppable droppableId="editor-canvas">
    {(provided) => (
      <div ref={provided.innerRef} {...provided.droppableProps}>
        {elements.map((element, index) => (
          <Draggable key={element.id} draggableId={element.id} index={index}>
```

### Warm & Software - Interactive 3D Art & Poetry Portfolio
[![Warm & Software Preview](./screenshots/warmandsoftware-preview.gif)](https://warmandsoftware.com)

**Immersive 3D Portfolio** | **React Three Fiber** | **React Spring** | **Custom Shaders** | **TypeScript**

A groundbreaking fusion of art, poetry, and technology:
- **Dynamic 3D Navigation** - Interactive menu system with physics-based animations
- **Procedural Art Generation** - Real-time particle systems and flowing curves
- **Poetry Integration** - Animated text experiences with custom typography
- **Mobile-Responsive 3D** - Optimized WebGL performance across devices
- **GPU-Accelerated Rendering** - Custom shaders and post-processing effects

```88:95:warmandsoftware/client/src/components/Lines.js
// Procedural line generation with Catmull-Rom curves
const curve = useMemo(() => {
  const points = [];
  for (let i = 0; i < 50; i++) {
    points.push(new THREE.Vector3(
      Math.sin(i * 0.1) * 10,
      Math.cos(i * 0.15) * 5,
      i * 0.5
    ));
  }
  return new THREE.CatmullRomCurve3(points);
}, []);
```

### WWJD2025 - Social Impact Interactive Timeline
[![WWJD2025 Preview](./screenshots/wwjd2025-preview.gif)](https://wwjd2025.com)

**Educational Platform** | **React 19** | **Three.js** | **Material-UI** | **Social Commentary**

A thought-provoking examination of policy through faith:
- **Interactive Policy Timeline** - Project 2025 proposals vs. Jesus' teachings
- **3D Data Visualization** - Immersive shader backgrounds and dynamic elements
- **Source Attribution** - Comprehensive citations from 40+ news sources
- **Print Resources** - Downloadable awareness materials and graphics
- **Responsive Design** - Optimized for education and discussion

```66:75:wwjd2025/src/App.js
// Comprehensive source mapping for policy verification
const sourceIconMap = {
  "New York Times": NYT,
  "The Guardian": TheGuardian,
  "Washington Post": WashingtonPost,
  "EPA": EPA,
  // ... 40+ verified sources
};
```

---

## Environmental Consciousness & Clean Technology

> "There is more than one story. There is more than one narrative. There is more than one protagonist... There is only one earth to which all belong."

Inspired by the interconnectedness of all things, I advocate for technology that serves both human progress and planetary stewardship. My work reflects a commitment to:

- **Sustainable Digital Practices** - Energy-efficient code and optimized performance
- **Environmental Awareness** - Projects that educate and inspire positive action
- **Inclusive Technology** - Solutions that consider impact on all communities
- **Ethical Innovation** - Technology development with conscience and purpose

---

## Technology Stack & Expertise

### **Frontend Excellence**
| Category | Technologies |
|----------|-------------|
| **Core** | React 18/19, TypeScript, Next.js |
| **3D Graphics** | Three.js, React Three Fiber, WebGL, GLSL Shaders |
| **Animation** | React Spring, Framer Motion, GSAP, CSS3 Animations |
| **UI/UX** | Material-UI, Ant Design, Styled Components, Tailwind CSS |
| **State Management** | Zustand, Valtio, Redux Toolkit, Context API |

### **Backend & Cloud**
| Category | Technologies |
|----------|-------------|
| **Runtime** | Node.js, Express.js, Serverless Functions |
| **Database** | MongoDB, PostgreSQL, AWS DynamoDB |
| **Cloud** | AWS (Lambda, S3, SES, CloudWatch), Vercel, Netlify |
| **Security** | JWT, bcrypt, CORS, Input Validation |

### **Development Tools**
| Category | Technologies |
|----------|-------------|
| **Build** | Webpack, Vite, Create React App |
| **Testing** | Jest, React Testing Library, Cypress |
| **Code Quality** | ESLint, Prettier, TypeScript |
| **DevOps** | Git, GitHub Actions, Docker |

---

## Design & Creative Skills

- **3D Modeling & Animation** - Blender, procedural generation
- **Graphic Design** - Adobe Creative Suite, Figma
- **User Experience** - Research, prototyping, accessibility
- **Visual Effects** - Post-processing, particle systems, shaders
- **Typography** - Custom fonts, responsive text systems

---

## Professional Approach

### **Development Philosophy**
- **Performance-First** - Optimized loading, smooth interactions, efficient rendering
- **Mobile-Centric** - Progressive enhancement, touch-optimized interfaces
- **Accessibility** - WCAG compliance, inclusive design principles
- **Security** - Defense-in-depth, secure coding practices
- **Scalability** - Modular architecture, maintainable codebases

### **Project Management**
- **Agile Methodology** - Iterative development, continuous improvement
- **Version Control** - Git flow, semantic versioning
- **Documentation** - Comprehensive READMEs, inline code comments
- **Testing Strategy** - Unit testing, integration testing, user acceptance
- **Deployment** - CI/CD pipelines, automated testing, monitoring

---

## Key Achievements

- **Enterprise-Grade Architecture** - Built scalable systems serving thousands of users
- **3D Web Innovation** - Pushed boundaries of browser-based 3D experiences
- **Performance Optimization** - Achieved 90+ Lighthouse scores consistently
- **Social Impact** - Created platforms that foster education and dialogue
- **Business Integration** - Successfully deployed client projects with real-world impact

---

## Let's Connect

I'm always excited to collaborate on innovative projects that make a positive impact. Whether you're looking for a full-stack developer, 3D experience creator, or technology consultant, I'd love to hear about your vision.

**Connect with me:**
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)
- **Portfolio**: [Your Personal Website](https://yourportfolio.com)
- **Email**: your.email@example.com

---

## Current Focus

Currently exploring:
- **AI Integration** - Machine learning applications in creative coding
- **WebXR** - Extended reality experiences for the web
- **Sustainable Tech** - Energy-efficient development practices
- **Community Building** - Open source contributions and knowledge sharing

---

*Built with ❤️ and a commitment to technology that serves humanity and our planet.*
