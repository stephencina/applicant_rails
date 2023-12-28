# applicant_rails

Follow the following steps if no dockerfile is provided or is not suitable for Mac M1 PC:

**Docker setup for Ruby on Rails using ruby 3.0.6**
- supports up to Rails 7.1


**Update ruby version on:**
- Modify `.ruby-verion` file
- Gemfile's `ruby "3.0.6"`


**Update gemfile.lock**
- RUBY VERSION ruby 3.0.6p216
- PLATFORMS aarch64-linux


**If applicant is using Rail's frontend:**
- http://localhost:50000/


**HOW TO RUN**
- docker-compose up -d --build
