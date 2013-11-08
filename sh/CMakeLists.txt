# CMake 2.6 or higher is required
cmake_minimum_required(VERSION 2.6)

# Give your project a suitable name
project("AuthorTools")

# Installation rules
install(FILES at-tex-worddist DESTINATION bin)
install(FILES at-tex-style at-tex-style-long at-tex-style-nominalizations at-tex-style-passive DESTINATION bin)
install(FILES at-tex-diction DESTINATION bin)
