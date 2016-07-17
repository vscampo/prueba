var maquina = {
    admin: {
        pass: "ficticiaMola"
    },
    consulta: {
        saldos: function(clave, usuario) {
                    var saldo = -1;
                    for (var i = 0; i < clientes.length; i++) {
                        if (clientes[i].usuario === usuario && clientes[i].password === clave) {
                            saldo = clientes[i].presupuesto;
                            break;
                        }
                    }
                    return saldo;
        },
        gastos: function(clave, usuario) {
            var gasto = false;
            for (var i = 0, i < clientes.length; i++) {
                if (clientes[i].usuario === usuario && clientes[i].password === clave) {
                    gasto = clientes[i].gastos;
                    break;
                }   

            }

            return gasto;
        }
    }

    agregarEliminar: {
        function asignar(nombre) {
            var usuario = false;

            for (var i = 0; i < clientes.length; i++) {
                if (clientes[i] === undefined) {
                    vacante = i;
                }
                if (clientes[i] === nombre) {
                    usuario = i;
                }
            }

            if (usuario || usuario === 0) {
                console.warn("Ya estabas registrado!");
                console.info("Eres el usuario", usuario);
            } else {
                if (vacante || vacante === 0) {
                    clientes[vacante] = nombre;
                    console.info("Eres el usuario ", vacante);
                    console.info("Felicidades!");
                }
            }

        },

        function quitar(nombre) {
            var usuario = false;

            for (var i = 0; i < clientes.length; i++) {
                if (clientes[i] === nombre) {
                    usuario = i;
                }
            }

            if (usuario || usuario === 0) {
                clientes[usuario] = undefined;
                console.info("El usuario " + nombre + " ha sido eliminado.");
            } else {
                console.warn("El usuario " + nombre + "... no existe!");
            }
        }

    }

    consultaProductos: {
        saldos: function(clave, usuario) {
                    var producto = -1;
                    for (var i = 0; i < clientes.length; i++) {
                        if (clientes[i].usuario === usuario && clientes[i].password === clave) {
                            producto = clientes[i].presupuesto;
                            break;
                        }
                    }
                    return producto;
        },
        gastos: function(clave, usuario) {
            var gasto = false;
            for (var i = 0, i < clientes.length; i++) {
                if (clientes[i].usuario === usuario && clientes[i].password === clave) {
                    gasto = clientes[i].gastos;
                    break;
                }   

            }

            return gasto;
        }
    }

};

var clientes = [{
    nombre: "alfredo",
    usuario: "alf",
    password: "alf123",
    tipoUsuario: "admin",
    gastos:[],
    presupuesto: 1000
}, {
    nombre: "rodolfo",
    usuario: "rodolf",
    password: "rodolf123",
    tipoUsuario: "user",
    gastos:[],
    presupuesto: 140
}, {
    nombre: "diego",
    usuario: "dieg",
    password: "diegf123",
    tipoUsuario: "user",
    gastos:[],
    presupuesto: 110
}];



var productos = [{
    nombre: "patatas",
    codigo: "a1",
    stock: 7,
    precio: 90
}, {
    nombre: "chocolate",
    codigo: "a2",
    stock: 10,
    precio: 60
}, {
    nombre: "zumo",
    codigo: "a3",
    stock: 10,
    precio: 30
}];
