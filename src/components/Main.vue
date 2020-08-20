<template>

	<div class="mx-5 px-5 pt-5 fs-12">
		
		<div class="px-4">
			<div class="content-tab d-flex justify-content-between fw-500">
				<div class="col-12 col-md-5 d-flex px-0">

					<div class="col px-0">
						<span>Overview</span>
					</div>

					<div class="col px-0">
						<span>Teams</span>
					</div>

					<div class="col px-0">
						<span>Modules</span>
					</div>

					<div class="col px-0">
						<span>Files</span>
					</div>

					<div class="col px-0">
						<span>Progress</span>
					</div>
				</div>
				<div class="col-12 col-md-6 d-flex px-0 justify-content-end">
					<div class="col-2 px-0">
						<span>All Tasks</span>
					</div>
					<div class="d-flex align-items-center col-3 px-0">
						<div class="toggleWrapper">
							<input type="checkbox" name="" class="mobileToggle" id="toggle" checked>
							<label for="toggle"></label>
						</div>
						<div>
							<span class="color-red">All Modules</span>
						</div>
					</div>

					<div class="col-5 d-flex px-0 justify-content-evenly">
						<div>
							<span class="icon clock-icon"></span>
						</div>
						<div>
							<span class="color-green ml-auto">Project Deadline : 6 weeks</span>
						</div>
					</div>

				</div>
			</div>

			<hr class="w-100">

			<div class="content mt-4 fs-14">
				<div class="component">
					<div class="d-flex justify-content-between font-weight-bold">
						<div>Backlog</div>
						<div class="px-2">
							<svg width="12" height="3" viewBox="0 0 12 3" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" fill="#03293D"/>
								<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" fill="#03293D"/>
								<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" fill="#03293D"/>
								<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
								<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
								<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
							</svg>																		
						</div>
					</div>
					<div class="card rounded mt-2 mb-3 text-center text-light-blue font-weight-bold shadow-sm border-0">
						+
					</div>
					<div class="mt-2 component-list list-contains fs-10">
						<div class="card rounded p-2 border-0 h-70 my-2">
							<div class="d-flex">
								<div>
									<span>Apply gredient colours on the 
										dashboard sidenav</span>
								</div>
								<div>
									<svg width="12" height="3" viewBox="0 0 12 3" fill="none" xmlns="http://www.w3.org/2000/svg">
										<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" fill="#03293D"/>
										<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" fill="#03293D"/>
										<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" fill="#03293D"/>
										<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
										<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
										<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
									</svg>												
								</div>
							</div>
							<div class="d-flex justify-content-between mt-auto">
								<div class="d-flex align-items-center">
									<span class="icon-medium clock-icon mr-1"></span>
									<span>Due Aug 8</span>
								</div>
								<div class="image-slide-8">
									<span class="one">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="two">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="three">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="four">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="more">+4</span>
								</div>
							</div>
						</div>

						<div class="card rounded p-2 border-0 h-70 my-2">
							<div class="d-flex">
								<div>
									<span>Apply gredient colours on the 
										dashboard sidenav</span>
								</div>
								<div>
									<svg width="12" height="3" viewBox="0 0 12 3" fill="none" xmlns="http://www.w3.org/2000/svg">
										<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" fill="#03293D"/>
										<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" fill="#03293D"/>
										<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" fill="#03293D"/>
										<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
										<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
										<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
									</svg>												
								</div>
							</div>
							<div class="d-flex justify-content-between mt-auto">
								<div class="d-flex align-items-center">
									<span class="icon-medium clock-icon mr-1"></span>
									<span>Due Aug 8</span>
								</div>
								<div class="image-slide-8">
									<span class="one">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="two">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="three">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="four">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="more">+4</span>
								</div>
							</div>
						</div>

						<div class="card rounded p-2 border-0 h-70 my-2">
							<div class="d-flex">
								<div>
									<span>Apply gredient colours on the 
										dashboard sidenav</span>
								</div>
								<div>
									<svg width="12" height="3" viewBox="0 0 12 3" fill="none" xmlns="http://www.w3.org/2000/svg">
										<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" fill="#03293D"/>
										<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" fill="#03293D"/>
										<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" fill="#03293D"/>
										<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
										<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
										<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
									</svg>												
								</div>
							</div>
							<div class="d-flex justify-content-between mt-auto">
								<div class="d-flex align-items-center">
									<span class="icon-medium clock-icon mr-1"></span>
									<span>Due Aug 8</span>
								</div>
								<div class="image-slide-8">
									<span class="one">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="two">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="three">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="four">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="more">+4</span>
								</div>
							</div>
						</div>

						<div class="card rounded p-2 border-0 h-70 my-2">
							<div class="d-flex">
								<div>
									<span>Apply gredient colours on the 
										dashboard sidenav</span>
								</div>
								<div>
									<svg width="12" height="3" viewBox="0 0 12 3" fill="none" xmlns="http://www.w3.org/2000/svg">
										<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" fill="#03293D"/>
										<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" fill="#03293D"/>
										<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" fill="#03293D"/>
										<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
										<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
										<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
									</svg>												
								</div>
							</div>
							<div class="d-flex justify-content-between mt-auto">
								<div class="d-flex align-items-center">
									<span class="icon-medium clock-icon mr-1"></span>
									<span>Due Aug 8</span>
								</div>
								<div class="image-slide-8">
									<span class="one">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="two">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="three">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="four">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="more">+4</span>
								</div>
							</div>
						</div>

						<div class="card rounded p-2 border-0 h-70 my-2">
							<div class="d-flex">
								<div>
									<span>Apply gredient colours on the 
										dashboard sidenav</span>
								</div>
								<div>
									<svg width="12" height="3" viewBox="0 0 12 3" fill="none" xmlns="http://www.w3.org/2000/svg">
										<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" fill="#03293D"/>
										<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" fill="#03293D"/>
										<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" fill="#03293D"/>
										<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
										<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
										<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
									</svg>												
								</div>
							</div>
							<div class="d-flex justify-content-between mt-auto">
								<div class="d-flex align-items-center">
									<span class="icon-medium clock-icon mr-1"></span>
									<span>Due Aug 8</span>
								</div>
								<div class="image-slide-8">
									<span class="one">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="two">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="three">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="four">
										<img src="../assets/pic.png" alt="" srcset="">
									</span>
									<span class="more">+4</span>
								</div>
							</div>
						</div>

					</div>
				</div>

				<div class="component">
					<div class="d-flex justify-content-between font-weight-bold">
						<div>Backlog</div>
						<div class="px-2">
							<svg width="12" height="3" viewBox="0 0 12 3" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" fill="#03293D"/>
								<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" fill="#03293D"/>
								<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" fill="#03293D"/>
								<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
								<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
								<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
							</svg>																		
						</div>
					</div>
					<div class="card rounded mt-2 text-center text-light-blue font-weight-bold shadow-sm border-0">
						+
					</div>
					<div class="mt-2 component-list fs-10">

					</div>
				</div>

				<div class="component">
					<div class="d-flex justify-content-between font-weight-bold">
						<div>Backlog</div>
						<div class="px-2">
							<svg width="12" height="3" viewBox="0 0 12 3" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" fill="#03293D"/>
								<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" fill="#03293D"/>
								<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" fill="#03293D"/>
								<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
								<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
								<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
							</svg>																		
						</div>
					</div>
					<div class="card rounded mt-2 text-center text-light-blue font-weight-bold shadow-sm border-0">
						+
					</div>
					<div class="mt-2 component-list fs-10">

					</div>
				</div>

				<div class="component">
					<div class="d-flex justify-content-between font-weight-bold">
						<div>Backlog</div>
						<div class="px-2">
							<svg width="12" height="3" viewBox="0 0 12 3" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" fill="#03293D"/>
								<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" fill="#03293D"/>
								<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" fill="#03293D"/>
								<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
								<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
								<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
							</svg>																		
						</div>
					</div>
					<div class="card rounded mt-2 text-center text-light-blue font-weight-bold shadow-sm border-0">
						+
					</div>
					<div class="mt-2 component-list fs-10">

					</div>
				</div>

				<div class="component">
					<div class="d-flex justify-content-between font-weight-bold">
						<div>Backlog</div>
						<div class="px-2">
							<svg width="12" height="3" viewBox="0 0 12 3" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" fill="#03293D"/>
								<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" fill="#03293D"/>
								<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" fill="#03293D"/>
								<path d="M6.625 1.625C6.625 1.27982 6.34518 1 6 1C5.65482 1 5.375 1.27982 5.375 1.625C5.375 1.97018 5.65482 2.25 6 2.25C6.34518 2.25 6.625 1.97018 6.625 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
								<path d="M2.25 1.625C2.25 1.27982 1.97018 1 1.625 1C1.27982 1 1 1.27982 1 1.625C1 1.97018 1.27982 2.25 1.625 2.25C1.97018 2.25 2.25 1.97018 2.25 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
								<path d="M11 1.625C11 1.27982 10.7202 1 10.375 1C10.0298 1 9.75 1.27982 9.75 1.625C9.75 1.97018 10.0298 2.25 10.375 2.25C10.7202 2.25 11 1.97018 11 1.625Z" stroke="#03293D" stroke-linecap="round" stroke-linejoin="round"/>
							</svg>																		
						</div>
					</div>
					<div class="card rounded mt-2 text-center text-light-blue font-weight-bold shadow-sm border-0">
						+
					</div>
					<div class="mt-2 component-list fs-10">

					</div>
				</div>
				
			</div>
		</div>
	</div>

</template>

<script>

export default {
  name: 'Main',
  props: {
    msg: String
  },
}
</script>

