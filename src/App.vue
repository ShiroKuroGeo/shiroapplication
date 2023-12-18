<!-- App.vue -->
<template>
  <nav class="navbar fixed-top shadow-sm navbar-expand-lg bg-light navbar-light py-3 py-lg-0 px-lg-5">
    <a href="index.html" class="navbar-brand ml-lg-3">
      <h1 class="m-0 display-5"><span class="text-warning">Shiro</span>Geo</h1>
    </a>
    <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse px-lg-3" id="navbarCollapse">
      <div class="navbar-nav m-auto py-0">
        <a href="#home" class="nav-item nav-link active">Home</a>
        <a href="#about" class="nav-item nav-link">About</a>
        <a href="#qualification" class="nav-item nav-link">Quality</a>
        <a href="#skill" class="nav-item nav-link">Skill</a>
        <a href="#service" class="nav-item nav-link">Service</a>
        <a href="#contact" class="nav-item nav-link">Contact</a>
      </div>
    </div>
  </nav>
  <div class="container-fluid bg-warning d-flex align-items-center mb-5 py-5" id="home" style="min-height: 100vh;">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-5 px-5 pl-lg-0 pb-5 pb-lg-0">
          <img class="img-fluid w-100 rounded-circle shadow-sm" src="./assets/img/profile.jpg" alt="">
        </div>
        <div class="col-lg-7 text-center text-lg-left">
          <h3 class="text-white font-weight-normal mb-3">I'm</h3>
          <h1 class="display-3 text-uppercase text-warning mb-2" style="-webkit-text-stroke: 2px #ffffff;">George Alfeser
            Inoc</h1>
          <h1 class="typed-text-output d-inline font-weight-lighter text-white"></h1>
          <div class="d-flex align-items-center justify-content-center justify-content-lg-start pt-5">
            <a href="#application" class="btn btn-outline-light mr-5">Application</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid py-5" id="about">
    <div class="container">
      <div class="position-relative d-flex align-items-center justify-content-center">
        <h1 class="display-1 text-uppercase text-white" style="-webkit-text-stroke: 1px #dee2e6;">About</h1>
        <h1 class="position-absolute text-uppercase text-warning">About Me</h1>
      </div>
      <div class="row align-items-center">
        <div class="col-lg-5 pb-4 pb-lg-0">
          <img class="img-fluid rounded w-100" src="./assets/img/about.jpg" alt="">
        </div>
        <div class="col-lg-7">
          <h3 class="mb-4">Full Stack Developer</h3>
          <p>
            I am a versatile full-stack developer proficient in both front-end technologies like Vue.js and back-end
            technologies like PHP with database PDO, ensuring end-to-end excellence in web application development.</p>
          <div class="row mb-3">
            <div class="col-sm-6 py-2">
              <h6>Name: <span class="text-muted">Inoc George Alfeser</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Birthday: <span class="text-muted">29 November 2001</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Degree: <span class="text-muted">Master</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Experience: <span class="text-muted">4 Years</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Phone: <span class="text-muted">09484750030</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Email: <span class="text-muted">inocgeorgealfeser@gmail.com</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Address: <span class="text-muted">Poblacion Cordova Cebu</span></h6>
            </div>
            <div class="col-sm-6 py-2">
              <h6>Freelance: <span class="text-muted">Available</span></h6>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid py-5" id="qualification">
    <div class="container">
      <div class="position-relative d-flex align-items-center justify-content-center">
        <h1 class="display-1 text-uppercase text-white" style="-webkit-text-stroke: 1px #dee2e6;">Quality</h1>
        <h1 class="position-absolute text-uppercase text-warning">Education & Expericence</h1>
      </div>
      <div class="row align-items-center">
        <div class="col-lg-6">
          <h3 class="mb-4">My Education</h3>
          <div class="border-left border-warning pt-2 pl-4 ml-2">
            <div class="position-relative mb-4">
              <i class="far fa-dot-circle text-warning position-absolute" style="top: 2px; left: -32px;"></i>
              <h5 class="font-weight-bold mb-1">Elementary</h5>
              <p class="mb-2"><strong>Cordova Elementary School</strong> | <small>2007 - 2013</small></p>
              <p>During my elementary education, I began cultivating foundational skills and a curiosity for learning,
                laying the groundwork for my academic journey and future pursuits.</p>
            </div>
            <div class="position-relative mb-4">
              <i class="far fa-dot-circle text-warning position-absolute" style="top: 2px; left: -32px;"></i>
              <h5 class="font-weight-bold mb-1">High School</h5>
              <p class="mb-2"><strong>Cordova National High School</strong> | <small>2013 - 2020</small></p>
              <p>In high school, I pursued a well-rounded education, fostering critical thinking and a passion for BSIT
                subjects, setting the stage for my academic and personal development.</p>
            </div>
            <div class="position-relative mb-4">
              <i class="far fa-dot-circle text-warning position-absolute" style="top: 2px; left: -32px;"></i>
              <h5 class="font-weight-bold mb-1">College</h5>
              <p class="mb-2"><strong>Cordova Public College</strong> | <small>2020 - 2024</small></p>
              <p>In college, I studied information technology, gaining a solid foundation in computer science, network
                management, and system administration to prepare for a dynamic career in the ever-evolving field of IT.
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <h3 class="mb-4">My Expericence</h3>
          <div class="border-left border-warning pt-2 pl-4 ml-2">
            <div class="position-relative mb-4">
              <i class="far fa-dot-circle text-warning position-absolute" style="top: 2px; left: -32px;"></i>
              <h5 class="font-weight-bold mb-1">Web Designer</h5>
              <p class="mb-2"><strong>Practice</strong> | <small>2020 - 2023</small></p>
              <p>Engaging in web design practice, I honed my skills by experimenting with various design principles,
                coding techniques, and user experience considerations, fostering a creative and technically adept approach
                to crafting visually appealing and functional websites.</p>
            </div>
            <div class="position-relative mb-4">
              <i class="far fa-dot-circle text-warning position-absolute" style="top: 2px; left: -32px;"></i>
              <h5 class="font-weight-bold mb-1">Business Logic & Database Logic</h5>
              <p class="mb-2"><strong>School</strong> | <small>2020 - 2023</small></p>
              <p>Diving into the realm of business logic, I dedicated myself to understanding the intricate frameworks and
                decision-making processes that drive successful enterprises, equipping me with a strategic mindset to
                integrate effective solutions and contribute meaningfully to business development.</p>
            </div>
            <div class="position-relative mb-4">
              <i class="far fa-dot-circle text-warning position-absolute" style="top: 2px; left: -32px;"></i>
              <h5 class="font-weight-bold mb-1">Full Stack</h5>
              <p class="mb-2"><strong>Freelancing</strong> | <small>2020 - 2023</small></p>
              <p>Embarking on freelancing, I navigated diverse projects, cultivating adaptability, client communication,
                and delivering high-quality solutions, fostering a dynamic and independent approach to my career in the
                ever-evolving landscape of freelance work.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid py-5" id="skill">
    <div class="container">
      <div class="position-relative d-flex align-items-center justify-content-center">
        <h1 class="display-1 text-uppercase text-white" style="-webkit-text-stroke: 1px #dee2e6;">Skills</h1>
        <h1 class="position-absolute text-uppercase text-warning">My Skills</h1>
      </div>
      <div class="row align-items-center">
        <div class="col-12">
          <div class="skill mb-4">
            <div class="d-flex justify-content-between">
              <h6 class="font-weight-bold">HTML</h6>
              <h6 class="font-weight-bold">95%</h6>
            </div>
            <div class="progress">
              <div class="progress-bar  bg-warning" role="progressbar" style="width: 95%" aria-valuenow="100"
                aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>
          <div class="skill mb-4">
            <div class="d-flex justify-content-between">
              <h6 class="font-weight-bold">CSS</h6>
              <h6 class="font-weight-bold">70%</h6>
            </div>
            <div class="progress">
              <div class="progress-bar  bg-warning" role="progressbar" style="width: 70%" aria-valuenow="100"
                aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>
          <div class="skill mb-4">
            <div class="d-flex justify-content-between">
              <h6 class="font-weight-bold">PHP</h6>
              <h6 class="font-weight-bold">95%</h6>
            </div>
            <div class="progress">
              <div class="progress-bar  bg-warning" role="progressbar" style="width: 95%" aria-valuenow="100"
                aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>
          <div class="skill mb-4">
            <div class="d-flex justify-content-between">
              <h6 class="font-weight-bold">Javascript</h6>
              <h6 class="font-weight-bold">50%</h6>
            </div>
            <div class="progress">
              <div class="progress-bar  bg-warning" role="progressbar" style="width: 50%" aria-valuenow="100"
                aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>
          <div class="skill mb-4">
            <div class="d-flex justify-content-between">
              <h6 class="font-weight-bold">Database Query</h6>
              <h6 class="font-weight-bold">100%</h6>
            </div>
            <div class="progress">
              <div class="progress-bar  bg-warning" role="progressbar" style="width: 100%" aria-valuenow="100"
                aria-valuemin="0" aria-valuemax="100"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid pt-5" id="service">
    <div class="container">
      <div class="position-relative d-flex align-items-center justify-content-center">
        <h1 class="display-1 text-uppercase text-white" style="-webkit-text-stroke: 1px #dee2e6;">Service</h1>
        <h1 class="position-absolute text-uppercase text-warning">My Services</h1>
      </div>
      <div class="row pb-3">
        <div class="col-lg-4 col-md-6 text-center mb-5">
          <div class="d-flex align-items-center justify-content-center mb-4">
            <i class="fa fa-2x fa-laptop service-icon bg-warning text-white mr-3"></i>
            <h4 class="font-weight-bold m-0">Web Design</h4>
          </div>
          <p>In web design, I craft visually captivating and user-centric interfaces that seamlessly blend aesthetics with
            functionality to elevate online experiences.</p>
        </div>
        <div class="col-lg-4 col-md-6 text-center mb-5">
          <div class="d-flex align-items-center justify-content-center mb-4">
            <i class="fa fa-2x fa-laptop-code service-icon bg-warning text-white mr-3"></i>
            <h4 class="font-weight-bold m-0">Web Development</h4>
          </div>
          <p>Through web development, I bring dynamic and scalable websites to life, utilizing cutting-edge technologies
            and coding practices for robust and efficient solutions.</p>
        </div>
        <div class="col-lg-4 col-md-6 text-center mb-5">
          <div class="d-flex align-items-center justify-content-center mb-4">
            <i class="fab fa-2x fa-android service-icon bg-warning text-white mr-3"></i>
            <h4 class="font-weight-bold m-0">Database Logic</h4>
          </div>
          <p>Specializing in database management, I design and optimize data architectures, ensuring secure,
            well-organized, and high-performance systems to support seamless information retrieval.</p>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid py-5" id="contact">
    <div class="container">
      <div class="position-relative d-flex align-items-center justify-content-center">
        <h1 class="display-1 text-uppercase text-white" style="-webkit-text-stroke: 1px #dee2e6;">Contact</h1>
        <h1 class="position-absolute text-uppercase text-warning">Contact Me</h1>
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-8">
          <div class="contact-form text-center">
            <div id="success"></div>
            <form name="sentMessage" id="contactForm" novalidate="novalidate">
              <div class="form-row">
                <div class="control-group col-sm-6">
                  <input type="text" class="form-control p-4" id="name" placeholder="Your Name" required="required"
                    data-validation-required-message="Please enter your name" />
                  <p class="help-block text-danger"></p>
                </div>
                <div class="control-group col-sm-6">
                  <input type="email" class="form-control p-4" id="email" placeholder="Your Email" required="required"
                    data-validation-required-message="Please enter your email" />
                  <p class="help-block text-danger"></p>
                </div>
              </div>
              <div class="control-group">
                <input type="text" class="form-control p-4" id="subject" placeholder="Subject" required="required"
                  data-validation-required-message="Please enter a subject" />
                <p class="help-block text-danger"></p>
              </div>
              <div class="control-group">
                <textarea class="form-control py-3 px-4" rows="5" id="message" placeholder="Message" required="required"
                  data-validation-required-message="Please enter your message"></textarea>
                <p class="help-block text-danger"></p>
              </div>
              <div>
                <button class="btn btn-outline-warning" type="submit" id="sendMessageButton">Send
                  Message</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
  <hr>
  <div class="container-fluid py-5" id="application">
    <div class="container">
      <div class="position-relative d-flex align-items-center justify-content-center">
        <h1 class="display-1 text-uppercase text-white" style="-webkit-text-stroke: 1px #dee2e6;">Application</h1>
        <h1 class="position-absolute text-uppercase text-warning">Scoring System</h1>
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-10">
          <div class="d-flex justify-content-between align-items-between">
            <span>Total: {{ totalScores }} </span> Mean Score: {{ averageScore }}
          </div>
          <table class="table">
            <thead>
              <tr>
                <th scope="col">#</th>
                <th scope="col">Name</th>
                <th scope="col">Subject</th>
                <th scope="col">Score</th>
                <th scope="col">Avarage Score</th>
                <th scope="col">Action</th>
              </tr>
            </thead>
            <tbody>
              <tr v-for="(to, index) of todos" :key="to.id">
                <th scope="row">{{ 1 + index++ }}</th>
                <td class="text-center">{{ to.name }}</td>
                <td class="text-center">{{ to.subject }}</td>
                <td class="text-center">{{ to.score }}</td>
                <td class="text-center">{{ parseInt(( to.score / totalScores ) * 100) }}</td>
                <td class="text-center">
                  <i class="fas fa-trash" @click="removeTask(to.id)" style="cursor: pointer"></i>
                </td>
              </tr>
            </tbody>
          </table>
          <button class="btn btn-warning btn-sm p-2 px-5 border" type="button" data-toggle="modal" data-target="#myModal"
            :disabled="totalTodos">Add Score</button>
          <div class="modal fade" id="myModal">
            <div class="modal-dialog modal-dialog-centered">
              <div class="modal-content">

                <!-- Modal Header -->
                <div class="modal-header">
                  Add Another Score 
                  <h4 class="modal-title"></h4>
                  <button type="button" class="close" data-dismiss="modal">&times;</button>
                </div>

                <div class="modal-body">
                  <div class="mb-3">
                    <label for="exampleInputEmail1" class="form-label">Full Name</label>
                    <input type="text" class="form-control" v-model="name" id="exampleInputEmail1"
                      placeholder="Enter Fullname">
                  </div>
                  <div class="mb-3">
                    <label for="exampleInputEmail1" class="form-label">Subjects</label>
                    <input type="text" class="form-control" v-model="subject" id="exampleInputEmail1"
                      placeholder="Enter Subejct">
                  </div>
                  <div class="mb-3">
                    <label for="exampleInputEmail1" class="form-label">Score</label>
                    <input type="number" class="form-control" v-model="score" id="exampleInputEmail1"
                      placeholder="Enter Score">
                  </div>
                </div>
                <div class="modal-footer">
                  <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                  <button type="button" class="btn btn-primary" @click="addGrade">Add Grade</button>
                </div>

              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid bg-warning text-white mt-5 py-5 px-sm-3 px-md-5">
    <div class="container text-center py-5">
      <div class="d-flex justify-content-center mb-4">
        <a class="btn btn-light btn-social mr-2" href="https://www.facebook.com/kurotoshirogeo/"><i
            class="fab fa-facebook-f"></i></a>
        <a class="btn btn-light btn-social" href="#"><i class="fab fa-instagram"></i></a>
      </div>
      <div class="d-flex justify-content-center mb-3">
        <a class="text-white" href="#">Privacy</a>
        <span class="px-3">|</span>
        <a class="text-white" href="#">Terms</a>
        <span class="px-3">|</span>
        <a class="text-white" href="#">FAQs</a>
        <span class="px-3">|</span>
        <a class="text-white" href="#">Help</a>
      </div>
      <p class="m-0">&copy; <span class="text-primary">Shiro George Alfeser Inoc</span>. All Rights Reserved. Designed
        by <a class="text-white font-weight-bold" href="https://htmlcodex.com">HTML Codex</a>
      </p>
    </div>
  </div>
</template>

<script setup>

import { ref, onMounted, computed } from 'vue'
import { db } from './firebase'
import { collection, query, onSnapshot, deleteDoc, doc, addDoc } from "firebase/firestore";

const name = ref('')
const subject = ref('')
const score = ref('')
const todos = ref([])
const scores = ref([])

const addGrade = async () => {
  try {
    await addDoc(collection(db, "grading"), {
      name: name.value,
      subject: subject.value,
      score: score.value,
    });
    name.value = ''
    subject.value = ''
    score.value = ''
  } catch (e) {
    console.log(e);
  }
}



const removeTask = (id) => {
  if (confirm('Are you sure want to remove this task?')) {
    const fsquery = doc(db, 'grading', id);
    deleteDoc(fsquery)
      .then(() => {
        console.log('Document successfully deleted.');
      })
      .catch((error) => {
        console.error('Error deleting document:', error);
      });
  }

}

const getGrading = () => {
  const q = query(collection(db, "grading"));
  onSnapshot(q, (querySnapshot) => {
    const newTask = [];
    const newScores = [];
    querySnapshot.forEach((doc) => {
      const todo = {
        id: doc.id,
        name: doc.data().name,
        subject: doc.data().subject,
        score: doc.data().score,
      }
      newTask.push(todo);
      newScores.push(doc.data().score);
    });
    todos.value = newTask;
    scores.value = newScores;
  });
}

const totalScores = computed(() => {
  return scores.value.reduce((sum, currentScore) => sum + currentScore, 0);
});

const totalTodos = computed(() => {
  return todos.value.length >= 9;
});

const averageScore = computed(() => {
  const total = scores.value.reduce((sum, currentScore) => sum + currentScore, 0);
  const numberOfTodos = todos.value.length;

  if (numberOfTodos === 0) {
    return 0; 
  }

  return total / numberOfTodos;
});

onMounted(() => {
  getGrading();
})

</script>