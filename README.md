# Spring_mvc
This repo contains spring mvc project.  Spring mvc gives more control on handling requests and rersponse.
Spring annotation feature helps in it. Different annotations used are 
@Controller 
This annotation is used to specify that particular class acts as a controller. The controller is responsible for processing incoming requests, preparing a model and returning the view to be rendered as a response 
@RestController 
This controller is used for handling rest requests.

@RequestMapping
This annotation is used to specify the request for which request the following function is to be executed.
Syntax = @RequestMapping(“home”)
@ResponseBody 
This annotation is used to send data of a function as a response body.

Note – 
Spring boot does auto configuration for finding view. But directory structure should be:
Src -------> main -----------> webapp
Here one thing to keep in mind that jsp are not directly shown on the web browser. You have to add a maven dependency to convert jsp into servlet. 
If you have different directory structure you can use- application.properties folder for manual configuration

@RequestParam
This annotation is used to assign the request parameter to the variables in the method formal parameters
Syntax = @RequestParam(“name”)

Also, ModelAndView is also used for accepting client data and setting view.
