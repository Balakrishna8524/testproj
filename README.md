# My PHP Projects Portfolio

<style>
/* Card styles */
.project-card {
  border: 1px solid #ddd;
  border-radius: 5px;
  width: 300px;
  margin: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  display: inline-block;
  vertical-align: top;
}

.project-card img {
  width: 100%;
  height: auto;
}

.project-card-title {
  padding: 15px;
  text-align: center;
  font-size: 18px;
  font-weight: bold;
}

/* Modal styles */
.modal {
  display: none;
  position: fixed;
  z-index: 1;
  padding-top: 100px;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: rgba(0, 0, 0, 0.8);
}

.modal-content {
  background-color: #fefefe;
  margin: auto;
  padding: 20px;
  border: 1px solid #888;
  width: 80%;
  max-width: 800px;
}

.close {
  color: #aaa;
  float: right;
  font-size: 28px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: black;
  text-decoration: none;
  cursor: pointer;
}

.project-details img {
  width: 100%;
  margin-bottom: 10px;
}
</style>

<!-- JavaScript for modal -->
<script>
function openModal(id) {
  document.getElementById(id).style.display = 'block';
}

function closeModal(id) {
  document.getElementById(id).style.display = 'none';
}
</script>

## Projects

<!-- Project Card -->
<div class="project-card" onclick="openModal('modal1')">
  <img src="https://via.placeholder.com/300" alt="Project 1">
  <div class="project-card-title">Project 1</div>
</div>

<!-- Modal for Project 1 -->
<div id="modal1" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal1')">&times;</span>
    <h2>Project 1</h2>
    <p>Description of Project 1</p>
    <div class="project-details">
      <img src="https://via.placeholder.com/600x400" alt="Screenshot 1">
      <img src="https://via.placeholder.com/600x400" alt="Screenshot 2">
      <img src="https://via.placeholder.com/600x400" alt="Screenshot 3">
    </div>
  </div>
</div>

<!-- Repeat for other projects -->
<div class="project-card" onclick="openModal('modal2')">
  <img src="https://via.placeholder.com/300" alt="Project 2">
  <div class="project-card-title">Project 2</div>
</div>

<div id="modal2" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal2')">&times;</span>
    <h2>Project 2</h2>
    <p>Description of Project 2</p>
    <div class="project-details">
      <img src="https://via.placeholder.com/600x400" alt="Screenshot 1">
      <img src="https://via.placeholder.com/600x400" alt="Screenshot 2">
      <img src="https://via.placeholder.com/600x400" alt="Screenshot 3">
    </div>
  </div>
</div>
