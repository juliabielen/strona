# Witam na mojej stronie! :)
# package pl.Julia.controllers;

import org.springframework.beans.factory.annotation.Autowired;

import org.springframework.stereotype.Controller;

import org.springframework.web.bind.annotation.RequestMapping;

import.pl.Julia.strona.ASSADAO;

@Controller
public class JuliaApplication {
    
    @Autowired
    ASSADAO dao;
    
    @RequestMapping("strona")
    public String mojaStrona {
    return "moja strona"
}
    @RequestMapping ("powitanie")
    public String powitanie {
    return "Witajcie!"
	}

}
