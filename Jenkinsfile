pipeline {
										agent any
										tools{
											jdk 'jdk11'
											maven 'Maven'
										}
										stages {
											stage('Hello') {
												steps {
												   git 'https://github.com/dev-patidar17/time-tracker.git'
												}
											}
											 stage('Compile') {
												  steps {
												   sh "mvn clean compile -Dskiptests=true"
												}
											 }
											
										}
									}
