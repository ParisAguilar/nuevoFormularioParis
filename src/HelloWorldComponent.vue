<template>
  <div>
    <nav class="navbar is-">
      <h1>Formulario</h1>
    </nav>

    <form>
      <div class="field">
        <label class="label">Nombre</label>
        <div class="control">
          <input
            class="input is-primary"
            type="text"
            placeholder="ingresa tu nombre"
          />
        </div>
      </div>
      <div class="field">
        <label class="label">Correo</label>
        <div class="control has-icons-left has-icons-right">
          <input
            class="input is-danger"
            type="email"
            placeholder="ingresa tu correo electrónico"
            value
          />
          <span class="icon is-small is-left">
            <i class="fas fa-envelope"></i>
          </span>
          <span class="icon is-small is-right">
            <i class="fas fa-exclamation-triangle"></i>
          </span>
        </div>
        <p class="help is-danger"></p>
      </div>

      <div class="field">
        <label class="label">Usuario</label>
        <div class="control has-icons-left has-icons-right">
          <input
            class="input is-success"
            type="text"
            placeholder="Usuario"
            value
          />
          <span class="icon is-small is-left">
            <i class="fas fa-user"></i>
          </span>
          <span class="icon is-small is-right">
            <i class="fas fa-check"></i>
          </span>
        </div>
        <p class="help is-success"></p>
      </div>
      <div class="field">
        <label class="label">contraseña</label>
        <div class="control">
          <input
            class="input is-primary"
            type="password"
            placeholder="ingresa contraseña"
          />
        </div>
      </div>
      <label class="checkbox">
        <input type="checkbox" />
        Recordar contraseña
      </label>

      <div class="field">
        <label class="label">Edad</label>
        <div class="control">
          <div class="select is-primary">
            <select>
              <option>Selecciona una.</option>
              <option>18</option>
              <option>19</option>
              <option>20</option>
              <option>21</option>
              <option>22</option>
              <option>23</option>
              <option>24</option>
              <option>25</option>
              <option>más</option>
            </select>
          </div>
        </div>
      </div>
      <div class="field">
        <label class="label">foto</label>
        <div class="control">
          <input class="input is-primary" type="file" placeholder="ddd" />
        </div>
        <p class="help"></p>
      </div>
      <div class="field">
        <label class="label">comentario</label>
        <div class="control">
          <textarea
            class="textarea is-primary"
            placeholder="Ingresa tu comentario, aquí."
          ></textarea>
        </div>
      </div>

      <div class="field">
        <div class="control is-primary">
          <label class="checkbox">
            <a href="#">terminos</a>
          </label>
        </div>
      </div>

      <div class="field">
        <div class="control">
          <label class="radio">
            <input type="radio" name="question" />
            acepto
          </label>
          <label class="radio is-primary">
            <input type="radio" name="question" />
            No acepto.
          </label>
        </div>
      </div>

      <div class="field is-grouped">
        <div class="control">
          <button class="button is-primary">enviar</button>
        </div>
        <div class="control">
          <button class="button is-text">Cancelar</button>
        </div>
      </div>
    </form>
  </div>
</template>

<style>
.field {
  width: 35%;
}
</style>

<script lang="ts" src="./HelloWorld.component.ts"></script>
